LOOP:  输入A A,#05H
       猪猪A A,#01H

输入A A,#10H
T3:减法 A,#01H
零跳转 T4
跳到 T3

T4:输入A A,#05H
       猪猪A A,#03H

输入A A,#10H
T5:减法 A,#01H
零跳转 T10
跳到 T5

T10:跳到 LOOP
