# IndexError--List-index-out-of-rage

>>> this is the basic property of list , but put you on trouble sometimes.
>>> lists indexing will return an error if there is no element at that index. any where you are working with list(in web scrappig, reading and writing different types of data using pandas) the only reason for the list index out of range , i hve faced this problem while i was scrapping h1 tag from a list of 100 urls , while i was doing this there were some website that does not have h1 tag due to this i was getting error. For example:


>>># Create a new list
>>>list1 = [1,2,3]    
>>print(list1[100] )

Python will throw this error on the output screen:

---------------------------------------------------------------------------
IndexError                                Traceback (most recent call last)
<ipython-input-22-af6d2015fa1f> in <module>()
----> 1 list1[100]

IndexError: list index out of range
