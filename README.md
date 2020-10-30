# 6-react-konular2-assignment


1. Hooks
   - Class & fonksıyonel component-bileşenler
   [okuma linki](https://medium.com/frontend-development-with-js/class-component-function-component-hooks-37140f07e9f9), [okuma linki 2](https://medium.com/@karakusnavy/react-hook-avantajlar%C4%B1-ve-eski-y%C3%B6ntem-class-yap%C4%B1lar%C4%B1-kar%C5%9F%C4%B1la%C5%9Ft%C4%B1rmas%C4%B1-dd20de59add1)
   
   - hooks nedir?[okuma linki](https://bylge.com/p/react-hooks-nedir-ve-neden-kullaniyoruz-5ea8d7995ebbb40008db096b), [video](https://www.youtube.com/watch?v=6jUG9Xgr4Kw&ab_channel=SpagettiCode) 
   - useState & useEffect [video 1](https://www.youtube.com/watch?v=5JgXDB9V0h0&list=PLXRxVej0t57ZfVutPXqJRCp07CCcemCEf&index=1),[video 2](https://www.youtube.com/watch?v=XIJL0r7I3kk&list=PLXRxVej0t57ZfVutPXqJRCp07CCcemCEf&index=2&ab_channel=Ali%C3%96zkan), [video 3](https://www.youtube.com/watch?v=Z1Dl1cYFsZE&list=PLXRxVej0t57ZfVutPXqJRCp07CCcemCEf&index=3&ab_channel=Ali%C3%96zkan),[video 4](https://www.youtube.com/watch?v=7O9qQzkqbhI&list=PLXRxVej0t57ZfVutPXqJRCp07CCcemCEf&index=4&ab_channel=Ali%C3%96zkan)
   - Custom hook nasıl yazılır? [video](https://www.youtube.com/watch?v=TlGptgwtpmE&list=PL8IHDq7oEkgFbkISL6q10N_lfrCFovNE1&index=2&ab_channel=ReactDersleri), 

2. React ile API çağırma
    [video içeriğinde örnek var](https://www.youtube.com/watch?v=xebP3a--z5o&list=PL8IHDq7oEkgFKYIoNuubfZMuhhgEukkAg&index=9&ab_channel=ReactDersleri), [okuma hook ile başlayan kısım](https://tr.reactjs.org/docs/faq-ajax.html)
    
3. Forms [video](https://www.youtube.com/watch?v=4-P_ESMChek&list=PL8IHDq7oEkgFKYIoNuubfZMuhhgEukkAg&index=8&ab_channel=ReactDersleri), [okuma](https://qastack.info.tr/programming/23427384/get-form-data-in-reactjs)


4. Third party React tools
   - UI toolkits
   - Utilities
   Third party React tools can roughly be divided into 2 categories:

1. UI toolkits
2. Utilities

### UI toolkits

These kind of component libraries serve to **structure your user interface**. If you've ever worked with a CSS framework, this is what it means.

Popular presentational component libraries are the following:

- [Semantic UI](https://react.semantic-ui.com/)
- [Material UI](https://material-ui.com/)
- [Shards](https://designrevision.com/docs/shards-react/getting-started)

All of these are called `UI toolkits` and provide components that structure a particular part of your page.

For example, Let's say you want to add a `button` component in your form. You could make it yourself. Or you could take it from the toolkit!

```js
import React from "react";
import { Button } from "semantic-ui-react";

const ButtonExampleButton = () => <Button>Click Here</Button>;

export default ButtonExampleButton;
```

### Utilities

There are also tools that solve certain problems within the React ecosystem.

- [Enzyme](https://github.com/airbnb/enzyme) is a React-specific component testing tool, that makes it easier to test your React Components' output
- [Redux](https://redux.js.org/introduction/getting-started) is a state management tool, used to make it possible to connect every component directly to the entire state and thus eliminates the need to use props or callbacks.
- [React Intl](https://github.com/formatjs/react-intl) is a tool that provides an application the ability to have multiple languages (English, Dutch, etc.) within the application

All of these tools are not necessarily React-specific, but allow us to use React in order to create more engaging, feature-rich applications.
   
   egsersiz
   https://www.freecodecamp.org/learn/front-end-libraries/react/
