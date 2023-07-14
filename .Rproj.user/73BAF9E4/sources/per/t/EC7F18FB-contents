#### Statistic class ####

### Creating Data ####
#### DADOS 1 ####
#Tamanho <- c(1.33, 1.34, 1.45, 1.55, 1.66, 1.78, 1.80, 1.90, 1.92, 1.95)
#Peso <- c(60, 65, 76, 77, 89, 91, 96, 100, 120, 122)
#Pessoa <- 1:10

#Dados <- cbind(Tamanho, Peso, Pessoa)

#Dados <- data.frame(Pessoa,
                    #Tamanho,
                    #Peso)

Dados <- read.csv2("data/PesoEAltura.csv") #leitura de dados

plot(Dados$Tamanho, Dados$Peso) #plot

analise <- lm(Dados$Peso ~ Dados$Tamanho) #analise

hist(Dados$Peso) #hist1
hist(Dados$Tamanho) #hist2

summary(analise) #resultado

#write.csv2(Dados[, -1], file = "PesoEAltura.csv")

### DADOS 2 ####
### Creating Data ####
#Tamanho <- rnorm(100, 50, 1)
#Mercurio <- runif(100, 0, 100)
#Dados2 <- data.frame("Tamanho da Tartaruga" = Tamanho,
                   # "Mercurio" = Mercurio)
#View(dadinhos)

dadinhos <- read.table("data/TartarugaXMercurio.txt", header = TRUE)

plot(dadinhos$Mercurio, dadinhos$Tamanho.da.Tartaruga)

resultado <- lm(dadinhos$Tamanho ~ dadinhos$Mercurio)

summary(resultado)

hist(dadinhos$Tamanho.da.Tartaruga)
hist(dadinhos$Mercurio)

