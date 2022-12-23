def nhapdulieu():
    print("nhap vao so nguyen duong n: ")
    n = int(input())
    while n < 0:
        print("nhap lai n: ")
        n = int(input())
    for i in range(0,n):
        print("nhap vao phan tu thu", i+1)
        tmp = int(input())
        while tmp < 0:
            print("gia tri nhap vao khong hop le, nhap lai:")
            tmp = int(input())
        lst.append(tmp)
    return lst 
def timchuso(lst):
    for i in lst:
        j = i
        while j >= 10:
            j = j//0
        if j % 2 != 0:
            print(i )
        end.
