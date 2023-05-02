# yunseong-modal-example

## how to install

```
npm i yunseong-modal-example
```

## usage

### trigger

you can serve modal trigger as components.

example:

```jsx
//...
<MyModal trigger={<button>Click me!</button>}>// modal contents</MyModal>
```

### content

you can give any content to children for custom your modal

```jsx
<MyModal trigger={<button>Click me!</button>}>
  <h2>MODAL TITLE</h2>
  <div> hello </div>
  <div> hello 2</div>
</MyModal>
```
