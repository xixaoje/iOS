- #if的使用

```
#if 的后面接的是表达式 (求表达式的值为真则编译code部分否则跳过)

 code ...

#endif
```

- #if 的表达式是在编译是求值的 

```
#ifdef的使用
#ifdef  GREAT   只要GREAT被#define定义过则编译code部分
code ...
#endif  
```


- #if defined的使用
```
#if defined(x)   (首先处理defined运算符， defiend运算符 一般用作表达式中的一部分，如果x这个宏有#defined定义把 defined(x) 替换为1 否则替换为0,替换后相当于#if 1或 #if 0 ，到这应该能明白了吧.不说了)
code ...
#endif 
```

### #if可以控制代码的执行与否
```
#if __has_feature(objc_arc)
//条件满足 ARC
#else
// MRC
-(oneway void)release
{
    
}

-(instancetype)retain
{
    return _instance;
}

//习惯
-(NSUInteger)retainCount
{
    return MAXFLOAT;
}
#endif

```