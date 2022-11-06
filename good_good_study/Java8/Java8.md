# 1.Lamada

一一总结

- Lamada表达式可以理解为一种匿名函数：他没有名称，但有参数列表、函数主体、返回类型，可能还会有一个可以抛出的异常列表。
- Lamada表达式可以让你的代码更加简洁的传递代码。
- 函数式接口就是仅仅声明了一个抽象方法的接口。
- 只有在接受函数式接口的地方才可以使用Lamada表达式。
- Lamada表达式允许你直接内联，为函数式接口的抽象方法提供实现，并且将整个表达式作为函数式接口的一个实例。
- Java8自带一些常用的函数式接口、放在java.util.function包里,包括Predicate<T>、Function<T、R>、Supplier<T>、Consumer<T>、&&BinaryOperator<T>。
- 为了避免装箱操作，对Predicate<T>、Function<T、R>等通用的函数式接口的原始类型特化：IntPredicate、IntToLongFuncation等。
- 环绕执行模式（即在方法所必须的代码中间，你需要执行点什么操作，比如分配资源和清理）可以配合Lamada提高灵活性和可重要性。
- Lamada表达式所需要代表的类型称为目标类型。
- 方法引用让你重复使用现有的方法实现并传递他们。
- Comparator、Predicate 和Funcation等函数式接口都有几个可以用来结合lamada表达式的默认方法。



