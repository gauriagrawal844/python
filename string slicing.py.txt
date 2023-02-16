a= "hello_python"
print("Whole string : ", a[:])  #a[0:len(a)]
print("index 1:",a[1])
print("index b/w 1 to 6:",a[1:6])  #including 0 but not 6(till 5)
print("index till 6:",a[:6])
print("index with diference of 2:",a[::2])
print("last value:",a[-1])   # a[len(a)-1]  -- 12-1=11 means it print 11th index element
print("a1:",a[:-5])
print('reverse string:',a[-1::-1])
print("reverse index with difference of 2:",a[-1::-2])
