
  * new Objective-C literials which was available only in iOS6, the literials category could add the new feature to iOS below iOS SDK 6, so you can use:

>  ```Objective-C
>     NSArray * a = @[obj1, obj2, obj3];
>     id obj = a[0]; // this literial need a new method which is only available under iOS 6, the literial category added the missing methods to array/dictionary.
>  ```

