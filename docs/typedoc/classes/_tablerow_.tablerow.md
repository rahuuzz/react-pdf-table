[@david.kucsai/react-pdf-table](../README.md) › [Globals](../globals.md) › ["TableRow"](../modules/_tablerow_.md) › [TableRow](_tablerow_.tablerow.md)

# Class: TableRow <**S, SS**>

This component describes how to display a row.

## Type parameters

▪ **S**

▪ **SS**

## Hierarchy

* PureComponent‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››

  ↳ **TableRow**

## Index

### Methods

* [UNSAFE_componentWillMount](_tablerow_.tablerow.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_tablerow_.tablerow.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_tablerow_.tablerow.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_tablerow_.tablerow.md#optional-componentdidcatch)
* [componentDidMount](_tablerow_.tablerow.md#optional-componentdidmount)
* [componentDidUpdate](_tablerow_.tablerow.md#optional-componentdidupdate)
* [componentWillMount](_tablerow_.tablerow.md#optional-componentwillmount)
* [componentWillReceiveProps](_tablerow_.tablerow.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_tablerow_.tablerow.md#optional-componentwillunmount)
* [componentWillUpdate](_tablerow_.tablerow.md#optional-componentwillupdate)
* [getSnapshotBeforeUpdate](_tablerow_.tablerow.md#optional-getsnapshotbeforeupdate)
* [render](_tablerow_.tablerow.md#render)
* [shouldComponentUpdate](_tablerow_.tablerow.md#optional-shouldcomponentupdate)

## Methods

### `Optional` UNSAFE_componentWillMount

▸ **UNSAFE_componentWillMount**(): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[UNSAFE_componentWillMount](_tablecell_.tablecell.md#optional-unsafe_componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:458

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillReceiveProps

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `nextContext`: any): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[UNSAFE_componentWillReceiveProps](_tablecell_.tablecell.md#optional-unsafe_componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:490

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `nextState`: Readonly‹S›, `nextContext`: any): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[UNSAFE_componentWillUpdate](_tablecell_.tablecell.md#optional-unsafe_componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:518

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`nextState` | Readonly‹S› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentDidCatch

▸ **componentDidCatch**(`error`: Error, `errorInfo`: ErrorInfo): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentDidCatch](_tablecell_.tablecell.md#optional-componentdidcatch)*

Defined in node_modules/@types/react/index.d.ts:397

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

**Parameters:**

Name | Type |
------ | ------ |
`error` | Error |
`errorInfo` | ErrorInfo |

**Returns:** *void*

___

### `Optional` componentDidMount

▸ **componentDidMount**(): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentDidMount](_tablecell_.tablecell.md#optional-componentdidmount)*

Defined in node_modules/@types/react/index.d.ts:376

Called immediately after a compoment is mounted. Setting state here will trigger re-rendering.

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `prevState`: Readonly‹S›, `snapshot?`: SS): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentDidUpdate](_tablecell_.tablecell.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:429

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`prevState` | Readonly‹S› |
`snapshot?` | SS |

**Returns:** *void*

___

### `Optional` componentWillMount

▸ **componentWillMount**(): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentWillMount](_tablecell_.tablecell.md#optional-componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:444

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` componentWillReceiveProps

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `nextContext`: any): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentWillReceiveProps](_tablecell_.tablecell.md#optional-componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:473

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentWillUnmount](_tablecell_.tablecell.md#optional-componentwillunmount)*

Defined in node_modules/@types/react/index.d.ts:392

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `nextState`: Readonly‹S›, `nextContext`: any): *void*

*Inherited from [TableCell](_tablecell_.tablecell.md).[componentWillUpdate](_tablecell_.tablecell.md#optional-componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:503

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`nextState` | Readonly‹S› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `prevState`: Readonly‹S›): *SS | null*

*Inherited from [TableCell](_tablecell_.tablecell.md).[getSnapshotBeforeUpdate](_tablecell_.tablecell.md#optional-getsnapshotbeforeupdate)*

Defined in node_modules/@types/react/index.d.ts:423

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`prevState` | Readonly‹S› |

**Returns:** *SS | null*

___

###  render

▸ **render**(): *Element‹›*

*Defined in [src/TableRow.tsx:29](https://github.com/dmk99/react-pdf-table/blob/875b9cf/src/TableRow.tsx#L29)*

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)››, `nextState`: Readonly‹S›, `nextContext`: any): *boolean*

*Inherited from [TableCell](_tablecell_.tablecell.md).[shouldComponentUpdate](_tablecell_.tablecell.md#optional-shouldcomponentupdate)*

Defined in node_modules/@types/react/index.d.ts:387

Called to determine whether the change in props and state should trigger a re-render.

`Component` always returns true.
`PureComponent` implements a shallow comparison on props and state and returns true if any
props or states have changed.

If false is returned, `Component#render`, `componentWillUpdate`
and `componentDidUpdate` will not be called.

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹Partial‹[TableBodyProps](../interfaces/_tablebody_.tablebodyprops.md)›› |
`nextState` | Readonly‹S› |
`nextContext` | any |

**Returns:** *boolean*
