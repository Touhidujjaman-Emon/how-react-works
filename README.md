# How does react work behind the scene

## Component vs Instance vs Element

### Component

![alt text](components-react.png)

### Instance

![alt text](component-instance.png)

### Element

![alt text](react-element.png)

### Element to Dom (HTML)

![alt text](<elemet-dom(html).png>)

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
