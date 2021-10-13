# Note week of `10/11`

## 10/11
* first was exam review
* `catch` can catch multiple exceptions

```java
public static void main(String[] args) throws MyException{
  int i = 0;
  int n = 7;
   
  try{
    int y = n/i;
    } 
    catch( ArithemicException e){
      System.out.println("learn something new");
      throw new MyException("wow");
    } 
    catch(Exception e){
      System.out.println("should not be here");
    }
    finally {
      System.out.println("pay attention to the order of catches");
    }
}
```

* order matters with `try` and `catch` exceptions
* finally will always be called

```java
public MyException(String mgs){
  System.out.println("MyException is nice");
}
```

* `throws` does nothing `try` `catch` is more like an if statement

illegal size exception attempt
```java
System.out.println("Enter size: ")
int size = System.in
try{
  size;
}
catch(IllegalSizeException){
  System.out.println("Size is out of bounds");
}
```

## 10/13

* `((int[]) i.get(0))[0];`: gets a specific item from a 2D ArrayList [in this case item (0,0)]
* `int[] a = new int[Integer.MAX_VALUE];`: usually results in a memory error
* `LinkedList<String> ltr = new LinkedList<>();`: Like array list and should try instead of ArrayList
* 

