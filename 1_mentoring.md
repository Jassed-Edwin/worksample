# worksample
##### Hello i am Mr James.
The reason you are having this erros is because of the dobble square bracket "[[      ]]" you have used in the two list of arrays. 
###### You can can slove this in two ways
- First, if you want your output in an array, you should remove one of the square bracket in your list "**b**"
> Example
```
array_A = np.array([[1, 2, 3]])
array_B = np.array([4, 5, 6])
np.dot(array_A,array_B)
Output: array([32])
```

- Secondly, if you dont want your output in an array, you should only have only one square bracket in both list "**a** and **b**
> Example
```
array_A = np.array([1, 2, 3])
array_B = np.array([4, 5, 6])
np.dot(array_A,array_B)
Output: 32
```

Please not that you only use dobble square bracket when working with more than one elements in a list as shown below
```
a = np.array([[1, 2, 3, 4], [5, 6, 7, 8], [9, 10, 11, 12]])
```
### Below are useful link to help you understand working with numpy arrays
- [Diver Learning Page](https://diver.diveintocode.jp/curriculums/1627)
- [Learn Numpy](https://numpy.org/doc/stable/index.html)
- [Datacamp](https://www.datacamp.com/community/tutorials/python-arrays?utm_source=adwords_ppc&utm_medium=cpc&utm_campaignid=1455363063&utm_adgroupid=65083631748&utm_device=c&utm_keyword=&utm_matchtype=b&utm_network=g&utm_adpostion=&utm_creative=332602034364&utm_targetid=aud-299261629574:dsa-429603003980&utm_loc_interest_ms=&utm_loc_physical_ms=9067844&gclid=CjwKCAiA7dKMBhBCEiwAO_crFC8ITvoGqSc1vKHuZbrPUGsGKpu-gusO8Rdd12wGavncZXMyeqvdTBoCv5cQAvD_BwE)
