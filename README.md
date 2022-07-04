# runner_up_code
if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
    arr=list(arr)
    s1=max(arr)
    list1=[]
    for i in arr:
        if i==s1:
            pass
        else:
            list1.append(i)
    s2=max(list1)
    print(s2)
    
