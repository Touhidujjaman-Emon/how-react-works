# How does react work behind the scene

## Component vs Instance vs Element

### Component

![alt text](components-react.png)

### Instance

![alt text](component-instance.png)

### Element

![alt text](react-element.png)

### Element to Dom (HTML)

![alt text](elemet-to-dom.png)

### Why cant we call component as function

```jsx
{
  TabContent({ item: content.at(activeTab) });
}
```

- It does not create an instance of the component
- it cant contain its name
- renders its return value as a child of the parent component.(become a **div** of parent component)
  ![alt text](wrong-way-to-use-components.png)
  ![alt text](cant-even-mahange-own-state.png)

## How components displayed in the screen

![alt text](how-component-displayed-on-the-screen.png)

## How render is triggered

![alt text](how-render-is-trigered.png)

## The render phase

### High level overview

![alt text](render-phase.png)

### What is virtual dom

![alt text](virtual-dom.png)

### What is reconciliation

![alt text](reconciliation.png)

### The reconciler Fiber

![alt text](the-reconciler-FIBER.png)

### Reconciliation in action

![alt text](reconciliation-in-action.png)

## Commit and Browser paint phase

![alt text](the-commit-and-browserpain-phase.png)

### It is ReactDom who writes the dom

![alt text](commit-and-browserpaint-2.png)

## recape

![alt text](recape.png)

## How diffing (algorithm) works

![alt text](how-diffing-works.png)
![alt text](how-diffing-works-2.png)

## The key prop

![alt text](the-key-prop.png)

### Stable Key (keys in lists)

![alt text](keys-in-lists-stableKey.png)

### Changing key (key prop to reset state)

![alt text](key-prop-to-reset-state-ChangingKey.png)
