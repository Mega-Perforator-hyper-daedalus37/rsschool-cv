# Bogdan Masnij
## How to contact: 
- email: bogdanmasnij67@gmail.com
## Self introduction: 
I'd like to study js.
## Skills: 
- A bit of html, css, js
- English B2
- JLPT 4
## Code examples: 
```js
export const createElement = ({
  tag = "div",
  parent,
  elementClass,
  text,
  id,
  attribute,
  eventObj,
}) => {
  const element = document.createElement(tag);
  if (elementClass) {
    element.classList.add(...elementClass);
  }
  element.textContent = text;
  if (id) {
    element.id = id;
  }
  if (attribute) {
    attribute.forEach((item) => {
      element.setAttribute(item.attribute, item.value || "");
    });
  }
  parent.append(element);
  if (eventObj) {
    element.addEventListener(eventObj.event, (event) => {
      eventObj.callbackFn(event);
    });
  }
  return element;
};

```
## Work Experience: 
- None
## Education: 
- 130 school
- College KKIBP
## English language: 
- B2
