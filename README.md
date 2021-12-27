# Simple library for json to excel converting.
###### Fast and simple  _Json to Excel_*!*

# Example.

main.py
```python
from JExcel.jexcel import JExcel


je = JExcel('data', 'converted')
je.create()
```

data.json
```json
{
	"One": 1,
	"Two": 2,
	"Three": 3,
	"Fourth": 4,
	"Five": 5,
	"Six": 6
}
```

It's will create file ```converted.xlsx```, where data will look like...
<br>
<br>
<img src="https://lh3.googleusercontent.com/fife/AAWUweUSykqlfAbRctgKjxc-5CmSBDbIX-2pDqYZROQfEUYsCbWmd_307A3CTYVtWF4qAQkgClpdlkVP2vZLRiYRZgAzFWvsoUUepfrIA7HF5uCW_GWjMUDLCy3dSjGZC3aNCDcYy96gc_SdIyJJUEuFwiyS6rZDVzJCicaPEd0wXoqliNqgJ7W38CLIZ0VCxdQDjdmzmykgM0Aa95i2uAs7P74scm4vQm6Y-ynX4p7Ylmx05G3-X5MllMDH1NsO5E875Jydv3yCgk-4mU-K0FWmi0qxLDgUXapnctCh-2fhmBAj43KEkruhI1k5_OgGMAQeAhgTBTNPZE-GbhV_6aTwDkPcFYRQDK3l6_715EHS6e1_Pirwu_RsIVGLx5IdF_2TnxIJvrmqgP62xEg28mXhQwa2xKTYPXPtnUmrkXjHp78hzTTx8n1RkD4CccN3ynscxpdbvKvCMuNiFRE0rmKGGFoAVz3clScacQPJ3H0VDsFRryWtMRgfPFRjQcta8CzODVNbjKELmozDcIAIrRaYv5VvD_IUlAgKaTCv6PGcdHcjYH4IPJUIGHyetUtbxMdB8hnHtBcTS4_OjxIqUxCPZUbXbFthtLslXrpkFaip36mQGCLOVGoSpGy69Q2BbHjb5SoHvA4rvyUxWU6x9QNMy8SjXAgVzaXnEXkZ6jITif6gwK6f9UJtpSO8MafaUaCyZgU8biyL9Uro_BSaCpHTg31O6ma6seeW-g=w2560-h937-ft">

Get version in code.
```python
from JExcel.jexcel import jev

# It's will print current version, on moment writing this documentation output will be 1,0.
print(jev())
```

# End.
Thanks for reading, have a good day, bye!
