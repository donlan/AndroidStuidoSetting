<!--
 * @Author: dooze 梁桂栋
 * @Email: stonelavender@hotmail.com
 * @Date: 2022-05-05 21:54:45
 * @LastEditors: dooze
 * @LastEditTime: 2022-05-05 22:08:37
 * @Description: 
-->
对于我个人而言能提升编码效率的Android Studio 设置

## Live Templates

AndroidXML

1. cmh
```
app:layout_constraintStart_toStartOf="parent"
app:layout_constraintEnd_toEndOf="parent"

```
2. cmid
```
app:layout_constraintStart_toStartOf="$id$"
app:layout_constraintEnd_toEndOf="$id$"
app:layout_constraintTop_toTopOf="$id$"
app:layout_constraintBottom_toBottomOf="$id$"
```
3. cmpa
```
app:layout_constraintStart_toStartOf="parent"
app:layout_constraintEnd_toEndOf="parent"
app:layout_constraintTop_toTopOf="parent"
app:layout_constraintBottom_toBottomOf="parent"
```
4. padh
```
android:paddingStart="$dp$"
android:paddingEnd="$dp$"
```
5. padv
```
android:paddingTop="$dp$"
android:paddingBottom="$dp$"
```  


Kotlin

1. livedata
```
private val _$name$ = MutableLiveData<$TYPE$>($VAL$)
val $name$: LiveData<$TYPE$> = _$name$
```