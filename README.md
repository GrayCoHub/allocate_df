Early model, but it works.  Will iterate through a df until it finds a cumulative value in the df which matches the test_value.

The row with this matching cum value is duplicated immediately below creating 2 identical rows.  

The value in the df which caused the cumulative value to exceed the test value is modified and reduced to become a value which 
makes the cum value equal to the test value.   

The new row below has the duplicated value become the diffeence from the value in the row above .., t/f the original value is split
between the first and second rows. 
