# find function
#find first occurrence

a= 'Hello pyThon'
print('l:',a.find('l'))
print('p:',a.find('p'))
print("pyThon: ",a.find("pyThon"))

b= 'Hello pyThon'
print('h:',b.find('h'))

c= 'Hello pyThon'
print('T:',c.find('T'))

#find other l
d= 'Hello pyThon'
print('2nd l:',d.find('l',3))  #3 means index no.3 (l) se right m find karna h

#if we find a value using find function that didn't exist in string then it will give us -1
e= 'Hello pyThon'
print('b did not exist:',e.find('b'))
