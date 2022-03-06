import random
def main():
  sta,order=map(int,input("start order").split()) #何個の点を打つか決める。
  for order in range(order):
    N=sta*10**order #orderは指数
    p=0
    for n in range(N):
      x=make_r()
      y=make_r()
      if x**2+y**2<=1:
        p+=1
    pi=4*p/N
    print("pi=",pi,"N=",N)

#0以上1以下の乱数作り関数
def make_r():
  while True:
    r=(random.random())*2
    if r>1:
      continue
    else:
      break
  return r
  
if __name__=="__main__":
  main()
