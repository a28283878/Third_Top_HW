# 1.4 
    1.Scientific applications
    – Fortran

    2.Business applications
    – COBOL

    3.Artificial intelligence
    – LISP

    4.Systems programming
    – C

    5.Web Software
    -PHP

# 1.18
多行註解

    優點 : writability 縮短註解多行程式碼的時間
   
    缺點 : reliability 有時會不小心註解到需要的程式碼
   

單行註解

    優點 : reliability 幾乎不會誤刪掉需要的程式碼
  
    缺點 : writability 需要花費大量的時間 如過要註解多行
  
# 2.14

    Typeless Languages 的優點在於資料的彈性，而缺點在於compiler無法判斷是否有發生宣告錯誤或是type衝突，必須要使用者自行負責。
    
# 3.4

    <assign> -> <id> = <expr>
    <id> -> A | B | C
    <expr> -> <expr> + <term> | <term>
    <term> -> <term> * <factor> | <factor>
    <factor> -> ( <expr> ) | <id> | <id> ++ | <id> - -

# 3.7
  
    <assign>
    <id>  =  <expr>
    A    =  <term>
    A    =  <term> * <factor>
    A    =  <factor> * ( <expr> )
    A    =  <id> * ( <expr> + <term> )
    A    =  A * ( <term> + <factor> )
    A    =  A * ( <factor> + <id> )
    A    =  A * ( <id> + C )
    A    =  A * ( B + C )
       
    <assign>
    <id> =  <expr>
    A   =  <term>
    A   =  <term> * <factor>
    A   =  <factor> * ( <expr> )
    A   =  <id> * ( <term> )
    A   =  B * ( <term> * <factor> )
    A   =  B * ( <factor> * ( <expr> ) )
    A   =  B * ( <id> * ( <expr> + <term> ) )
    A   =  B * ( C * ( <term> + <factor> ) )
    A   =  B * ( C * ( <factor> + <id> ) )
    A   =  B * ( C * ( <id> + B ) )
    A   =  B * ( C * ( A + B ) )
   
# 3.8

    http://www.cse.scu.edu/~rdaniels/html/courses/Coen171/HW1Soln.htm No.5
    
# 3.11
    
    (a) (b)

# 3.13

      <S> -> <A> b
      <A> -> a <A> b | ab
      
# 3.23

    1.  c > 8
    
    2.  b = 1/2
    
# 5.6

    Static Scope : 
      In sub1: sub1
      In sub2: sub1
      In sub3: main
    
    Dynamic Scope :
      In sub1: sub1
      In sub2: sub1
      In sub3: sub1
    
# 5.8
    
    Visible in Sub1:
      A, Y, Z --------- obtained from Sub1
      X --------- obtained from Main
      
    Visible in Sub2:
      A, B, Z --------- obtained from Sub2
      Y --------- obtained from Sub1
      X --------- obtained from Main
      
    Visible in Sub3:
      A, X, W --------- obtained from Sub2
      Y, Z --------- obtained from Main









