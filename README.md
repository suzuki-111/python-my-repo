# python-my-repo

#ユークリッドの互除法

x = 448
y = 48

var = x % y

x = y
y = var

while var != 0:
    var = x % y
    x = y
    y = var

print(x)