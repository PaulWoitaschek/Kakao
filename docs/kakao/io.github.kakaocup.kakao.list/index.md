[kakao](../index.md) / [io.github.kakaocup.kakao.list](./index.md)

## Package io.github.kakaocup.kakao.list

### Types

| Name | Summary |
|---|---|
| [AbsListViewAdapterActions](-abs-list-view-adapter-actions/index.md) | `interface AbsListViewAdapterActions` |
| [AbsListViewAdapterAssertions](-abs-list-view-adapter-assertions/index.md) | `interface AbsListViewAdapterAssertions : `[`AdapterAssertions`](../io.github.kakaocup.kakao.common.assertions/-adapter-assertions/index.md)<br>Provides assertions for AbsListView adapter |
| [DataBuilder](-data-builder/index.md) | `class DataBuilder`<br>Class for building data matchers |
| [KAbsListView](-k-abs-list-view/index.md) | `class KAbsListView : `[`ScrollViewActions`](../io.github.kakaocup.kakao.scroll/-scroll-view-actions/index.md)`, `[`AbsListViewAdapterActions`](-abs-list-view-adapter-actions/index.md)`, `[`BaseAssertions`](../io.github.kakaocup.kakao.common.assertions/-base-assertions/index.md)`, `[`AbsListViewAdapterAssertions`](-abs-list-view-adapter-assertions/index.md)<br>View with ScrollViewActions and BaseAssertions. Gives access to it's children |
| [KAdapterItem](-k-adapter-item/index.md) | `open class KAdapterItem<out T> : `[`BaseActions`](../io.github.kakaocup.kakao.common.actions/-base-actions/index.md)`, `[`BaseAssertions`](../io.github.kakaocup.kakao.common.assertions/-base-assertions/index.md)`, `[`Interceptable`](../io.github.kakaocup.kakao.intercept/-interceptable/index.md)`<ViewInteraction, ViewAssertion, ViewAction>`<br>Base class for KAbsListView adapter items |
| [KAdapterItemType](-k-adapter-item-type/index.md) | `class KAdapterItemType<out T : `[`KAdapterItem`](-k-adapter-item/index.md)`<*>>`<br>For internal use. Don't use manually. |
| [KAdapterItemTypeBuilder](-k-adapter-item-type-builder/index.md) | `class KAdapterItemTypeBuilder`<br>Class that maps types to providing functions |
| [KEmptyAdapterItem](-k-empty-adapter-item/index.md) | `class KEmptyAdapterItem : `[`KAdapterItem`](-k-adapter-item/index.md)`<`[`KEmptyAdapterItem`](-k-empty-adapter-item/index.md)`>`<br>Empty implementation of KAdapterItem |