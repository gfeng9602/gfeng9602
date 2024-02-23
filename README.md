- 👋 Hi, I’m @gfeng9602
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
gfeng9602/gfeng9602 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
"""
程序开头注释
author: xingbuxing
date: 2018年01月11日
功能：本程序主要介绍python的条件语句、循环语句
"""

**
# =====条件语句介绍
# 条件语句语法如下：
"""
if 条件A（结果为布尔值，true或者False）:
    执行相关操作1（需要使用tab缩进）
    ......

elif 条件B（结果为布尔值，true或者False）:
    执行相关操作2
    ......
    
else:
    执行相关操作3
"""

# 条件语句解释说明如下：
"""
1. 若条件A为True，那么执行相关操作1，程序结束
2. 若条件A为False，那么判断条件B，若条件B为True，那么执行相关操作2，程序结束
3. 若条件A为False，那么判断条件B，若条件B为False，那么执行相关操作3，程序结束
4. elif并非是必须
"""

# 条件语句示例：根据symbol代码，判断币的计价单位
# symbol = 'xrpusd'  # 尝试将symbol改成'xrpbtc'，'xrpeth', 'xrpbnb'看相关结果。
# if symbol.endswith('usd'):
#     print(symbol, '以美元计价')
# elif symbol.endswith('btc'):
#     print(symbol, '以比特币计价')
# elif symbol.endswith('eth'):
#     print(symbol, '以以太坊计价')
# else:
#     print(symbol, '不知道以什么计价')


# =====循环语句
"""
循环语句帮助我们做重复的事情。
理论上重复3遍及以上的事情，都要交给循环语句来做。
"""

# ===for循环语句介绍
# for循环是最常用的循环语句

# 案例1：顺序循环输出一个list中的所有的元素
# for symbol in ['btcusd', 'ethusd', 'xrpusd']:  # 其中symbol是变量名，可以任意取名
#     print(symbol)  # 使用tab进行缩进
# a = ['btcusd', 'ethusd', 'xrpusd'] # 自学记录，针对LIST中间的每一个元素进循环
# print(a[0])
# print(a[1])
# print(a[2])
# for symbol in ['btcusd', 'ethusd', 'xrpusd']:
#     print(symbol)


# 案例2：计算1+2+3+……+10
# sum_num = 0  # 用于存储计算的结果
# for i in range(10+1):
#     sum_num += i  # 此处需要使用tab按键进行缩进
#     print(i, sum_num)
# print(sum_num)

# sum_num = 0 # 自学，计算1+2+3+……+10
# for i in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]:
#     sum_num += i
#     print(i, sum_num)
# print(sum_num)

sum_num = 0 # 自学，  此行代码用于存储计算的结果
# for i in range(10+1):
#     sum_num += i
#     print(i, sum_num)

# 案例3：批量判断币的计价单位
# symbol_list = ['btcusd', 'xrpbtc', 'xrpusd', 'xrpeth', 'ethusd', 'xrpbnb']
# for symbol in symbol_list:
#     if symbol.endswith('usd'):
#         print(symbol, '以美元计价')
#         continue  # continue用于不执行之后的语句，立即进入下一个循环，
#     if symbol.endswith('btc'):
#         print(symbol, '以比特币计价')
#         continue
#     if symbol.endswith('eth'):
#         print(symbol, '以以太坊计价')
#         continue
#     print(symbol, '不知道以什么计价')

symbol_list = ['btcusd', 'xrpbtc', 'xrpusd', 'xrpeth', 'ethusd', 'xrpbnb'] # 自学
# for i in symbol_list:
#     if i.endswith('usd'):
#         print(i, '以美元计价')
#         continue # 在循环语句当中使用，用于不执行之后的语句，立即进入下一个循环
#     if i.endswith('btc'):
#         print(i, '以比特币计价')
#         continue
#     print(i, '不知道以什么计价')



# ===while语句
# while语句语法如下：
"""
while 条件A:
    执行相关操作1（需要使用tab缩进）
    ......
"""

# while语句解释说明如下：
"""
1. 判断条件A，若条件A为False，那么程序结束。
2. 判断条件A，若条件A为True，那么执行相关操作1。
3. 然后再次判断条件A，重复上面的步骤
"""

# while语句案例1：计算1+2+3+……+10
# num = 1
# max_num = 10
# sum_num = 0  # 存储计算结果
# while num <= max_num:
#     sum_num += num
#     num += 1
#     print(num, sum_num)
#
# print(sum_num)

# while语句案例2：计算1+2+3+……+10
# num = 1
# max_num = 10
# sum_num = 0
# while True:
#     sum_num += num
#     num += 1
#     print(sum_num, num)
#     if num == max_num+1:**
#         break  # break用于跳出循环。for循环也适用
