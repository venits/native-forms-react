## [NativeForms](https://nativeforms.com)

### Build **forms, surveys & polls** for React.

### Why this product was created?

We created NativeForms to save you countless hours of boring development of forms. Create forms without coding and control them from the [dashboard](https://app.nativeforms.com). Bring all the logic outside your website, so you can control forms even when your website is live.

- [Installation](#installation)
- [Basic Usage](#basic-usage)
- [Props](#props)
- [Support](#support)

### Installation

```js
npm install native-forms-react --save
// or
yarn add native-forms-react
```

### Basic Usage

1. Import component.

```js
import NativeForms from "native-forms-react";
```

2. Render form.

```js
<NativeForms form="https://form.nativeforms.com/I2Z5xWPmZic4JlRvpmNy0Db" />
```

Replace **form prop** with your form's address. You can create your own forms [here](https://app.nativeforms.com).

### Props

| Name          | Type     | Required | Note                                                                                                                                 |
| ------------- | -------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------ | --- |
| **form**      | String   | **Yes**  | URL of **form** to display.                                                                                                          |
| **formJSON**  | Object   | No       | You can use JSON format of the form instead of _form URL_. You can get this format by clicking **Export Form to JSON** in dashboard. |
| **onClose**   | Function | No       | Called when user decides to close the form.                                                                                          |
| **onSend**    | Function | No       | Called when user **completes** form.                                                                                                 |     |
| **email**     | String   | No       | Email of person that will complete form (it will be displayed in the admin panel).                                                   |
| **name**      | String   | No       | Name of person that will complete form.                                                                                              |
| **extraData** | Object   | No       | Extra data fields that will be sent along with the completed form. This data will not be visible by users.                           |

### Support

In case of any questions or problems, please contact me at:
[hello@nativeforms.com](mailto:hello@nativeforms.com)

### Happy Coding 💖
