```R
ggmap(get_googlemap(center = c(120, 32), zoom = 4,maptype='roadmap')) + 
  geom_path(data = mark1, aes(x=lon, y=la, group=group), color="red") + 
  geom_path(data = mark2, aes(x=lon, y=la, group=group), color="orange") +
  geom_path(data = mark3, aes(x=lon, y=la, group=group), color="yellow") +
  geom_path(data = mark4, aes(x=lon, y=la, group=group), color="green") +
  geom_path(data = mark5, aes(x=lon, y=la, group=group), color="black") +
  geom_path(data = mark6, aes(x=lon, y=la, group=group), color="blue") + 
  geom_path(data = mark7, aes(x=lon, y=la, group=group), color="purple")
```
