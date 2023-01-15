Download [ `THIS` ](https://drive.google.com/file/d/1PfaXViODtQ7cbEuZ0yfFU9RxBBK7IyBj/view?usp=sharing) as project starter.

Submit your test to `iiem.ahmad@ukur.com` via Email with subject `TEST MOBILE DEVELOPER` , and attach your `sourcode` or `github repo link` and the compiled app.

---

<details><summary>-- OPEN THIS --</summary>

```dart
method = 'GET';

baseUrl = 'https://c50f007f-bad3-4e64-982d-fce35e877b09.mock.pstmn.io';

path = 'users';

query parameters = {'page' : <int>PAGE_ID}; // PAGE_ID start from 0

// These endpoint rely on mockup APIs that are not always available.
// If this occurs, you are allowed to mock the data using the users_responses.json file. 
```

The tests is :
 
1. Create a page that displays a list of users from the request to the endpoint above and display it using the `LAZY LOAD` strategy.
2. Create a feature to `search for users` using `name`,  `company` name,  or `both` as parameters.
3. Create a feature to `filter users` using the `registered` (parameter) date range.
4. Create a feature to `filter users` using `isActive` and `gender` as parameters.
5. Make a page that displays information about `selected users` from the users list page. 

Use [ `bloc` or `cubit` ](https://pub.dev/packages/bloc) package as state manager.

Write your code cleanly and efficiently.

</details>
