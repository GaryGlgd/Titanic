train <- read.csv("train.csv", sep = ";", stringsAsFactors = FALSE)
test <- read.csv("test.csv", sep = ";", stringsAsFactors = FALSE)
titanic <- bind_rows(train, test)

View(titanic)
ncol(titanic)
nrow(titanic)

summary(titanic)

ggplot(titanic, aes(x = survived, y = sex, color = pclass)) +
  geom_jitter()

ggplot(titanic, aes(x = survived, y = sex, color = age)) + 
  geom_jitter()
