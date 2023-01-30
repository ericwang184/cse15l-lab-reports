# Lab 2 Report
## Part 2
For the listExamples class, there was a bug in the merge method. One failure-inducing input is written below as a test.
```
    @Test
    public void testMerge(){
        List<String> list5 = new ArrayList<String>();
        list5.add("big");
        List<String> list6 = new ArrayList<String>();
        list6.add("freak");
        List<String> list7 = new ArrayList<String>();
        list7.add("big");
        list7.add("freak");
        assertEquals(list7, ListExamples.merge(list5, list6));
    }
```
There's also inputs that don't induce a failure, such as the test written below.
```
    @Test
    public void testMerge(){
        List<String> list8 = new ArrayList<String>();
        List<String> list2 = new ArrayList<String>();
        list2.add("big");
        list2.add("cop");
        list2.add("food");
        assertEquals(list2, ListExamples.merge(list2, list8));
    }
```
From the screenshot below, if we run the test for the failure-inducing input that I wrote above, there is an memory error. However, the merge method should return the two lists together in one array in sorted order. 

From the screenshot below, if we run the test for the input that doesn't induce a failure, we see that it passes the test. 
    
## Part 3

