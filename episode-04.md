- create data structure
```
cats <- data.frame(coat = c("calico", "black", "tabby"),
                    weight = c(2.1, 5.0, 3.2),
                    likes_catnip = c(1, 0, 1))
```
- save to file
```
write.csv(x = cats, file = "data/feline-data.csv", row.names = FALSE)
```
