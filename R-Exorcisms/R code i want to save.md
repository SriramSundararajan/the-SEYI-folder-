> suspensionFeeding <- subset(bodySize, feeding ==1)
> depositFeeding <- subset(bodySise, feeding ==2)
Error in subset(bodySise, feeding == 2) : object 'bodySise' not found
> depositFeeding <- subset(bodySize, feeding ==2)
> miningFeeding <- subset(bodySize, feeding ==3)
> grazingFeeding <- subset(bodySize, feeding ==3)
> predatoryFeeding <- subset(bodySize, feeding ==4)
> grazingFeeding <- subset(bodySize, feeding ==4)
> predatoryFeeding <- subset(bodySize, feeding ==5)
> otherFeeding <- subset(bodySize, feeding ==6)
> 
> 
> 
> 
> 
> 

so
sizeData$feeding <- factor(sizeData$feeding)
extRate <- data.frame(interval = timescale$interval_name)
meanSize <- extRate
for(i in 1:nrow(timescale)) {
temp <- subset(sizeData, fad_age > timescale$age_top[i] & lad_age < timescale$age_bottom[i]
tempSize <- tapply(log10(temp$max_vol), temp$feeding, mean)
meanSize[i,2:7] <- as.numeric(temp_size)
tempExt <- subset(temp, lad_age > = timescale$age_top[i] & lad_age < timescale$age_bottom[i])
tempExt <- table(tempExt$feeding)
totalDiv <- table(temp$feeding)
extRate[i,2:7] <- as.numerical(tempExt) / as.numeric(totalDiv)