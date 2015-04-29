@Test(expected=ArithmeticException.class)   
public void testDivide() {   
assertEquals(3,Math.divide(9,3));   
assertEquals(3,Math.divide(10,3));   
Math.divide(10,0); //除数不能为0，会抛出异常   
}   

@Ignore("忽略乘法测试")   
@Test  
public void testMultiple() {   
} 

@Test(expected=ArithmeticException.class)
public void testDivide() {
assertEquals(3,Math.divide(9,3));
assertEquals(3,Math.divide(10,3));
Math.divide(10,0); //除数不能为0，会抛出异常
}

@Ignore("忽略乘法测试")
@Test
public void testMultiple() {
}
