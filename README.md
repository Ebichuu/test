# test
# 变量

message ="aaa"
print(message)
aaa
-  
name = "ada lovelace"
print(name.title())
print(name.lower())
Ada Lovelace
ada lovelace

    大小写

first_name ="ada"

last_name = "lovelace"

full_name = first_name + " " +last_name

print("hello," + full_name.title() + "!")

hello,Ada Lovelace!

print("\tPython")

	Python

    制表符 \t

print("Languages:\nPython\nC")

Languages:
Python
C

    换行符 \n

a =" python "

a

' python '

a.rstrip()

' python'

a.lstrip()

'python '

    删除空白符 strip() lstrip()

0.2+0.1

0.30000000000000004

0.1*3

0.30000000000000004

age = 23

a = "happy" + str(age) + "rd Birthday!"

print(a)

happy23rd Birthday!

    str()

import this

The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!

## 列表

a = ['1','2','3']

print(a)

print(a[2])

3

print(a[1])

2

print(a[-1])

3

a = ['1','2','3']

a[0] = '4'

print(a)

['4', '2', '3']

    修改

a = ['1','2','3']

print(a)

​

a.append('4')

print(a)

['1', '2', '3']
['1', '2', '3', '4']

a = []

​

a.append('1')

a.append('2')

a.append('3')

​

print(a)

['1', '2', '3']

    列表末尾添加 .append

a = ['1','2','3']

a.insert(0,'4')

print(a)

['4', '1', '2', '3']

    在列表中插入元素

a = ['1','2','3']

print(a)

del a[0]

print(a)

['1', '2', '3']
['2', '3']

    在列表删除元素 del

a = ['1','2','3']

print(a)

​

popped_a =a.pop()

print(a)

print(popped_a)

['1', '2', '3']
['1', '2']
3

a = ['1','2','3']

​

last_haha =a.pop()

print("last was a"+last_haha.title())

last was a3

- 使用pop() 删除列末元素

a = ['1','2','3']

​

first_haha = a.pop(0)

print("first was a"+first_haha.title())

first was a1

    弹出任何位置元素

a = ['1','2','3']

print(a)

​

a.remove('1')

print(a)

['1', '2', '3']
['2', '3']

a = ['1','2','3']

print(a)

​

haha = '1'

a.remove(haha)

print(a)

print(haha + ",is me")

['1', '2', '3']
['2', '3']
1,is me

​

b = ['asasas','bsbsb','sasasa']

b.sort()

print(b)

['asasas', 'bsbsb', 'sasasa']

b = ['asasas','bsbsb','sasasa']

b.sort(reverse=True)

print(b)

['sasasa', 'bsbsb', 'asasas']

    使用sort() 与传递参数reverse=True，对列表哦按字母顺序以及相反排序
        永久

b = ['bsasas','ssbsb','aasasa']

print("原始的 original")

print(b)

print("整理的 sorted")

print(sorted(b))

print("list again")

print(b)

原始的 original
['bsasas', 'ssbsb', 'aasasa']
整理的 sorted
['aasasa', 'bsasas', 'ssbsb']
list again
['bsasas', 'ssbsb', 'aasasa']

    使用sorted() 对列表临时排序

b = ['bsasas','ssbsb','aasasa']

print(b)

​

b.reverse()

print(b)

['bsasas', 'ssbsb', 'aasasa']
['aasasa', 'ssbsb', 'bsasas']

    反转列表顺序 reverse()
