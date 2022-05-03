# React-Component-tree-start

## App.jsx

```js
{
  items.map((todoItem, index) => (
    <ToDoItem key={index} id={index} text={todoItem} />
  ));
}
```

## Todo.jsx

```js
<li style={{ textDecoration: isDone ? "line-through" : "none" }}>
  {props.text}
</li>
```

Created with CodeSandbox
