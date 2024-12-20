# Some vs Any keywords
## Similarities
- Both some and any can be used with Protocol that have associatedtype in it.
## Differences
### Homogeneous vs Heterogenous collection behaviour
- some: homogeneous collection - only similar conforming type are allowed inside the collection.
- any: heterogenous collection - any conforming type is allowed inside the collection
### Similar return type
- some: only allows some conforming type to be returned
- any: allows any conforming type to be returned
----------------
```
struct BottomSheetWithBlurBackground<IndicatorView: View, InsideContentView: View>: ViewModifier {
  let blurRadius: CGFloat
  let cornerRadius: CGFloat
  let indicatorView: IndicatorView
  let snapRatio: CGFloat
  let minHeightRatio: CGFloat
  let insideContentView: InsideContentView
```
why need to use generic here? not any View?
