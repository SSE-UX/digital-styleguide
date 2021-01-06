# Buttons

## Introduction

Buttons are used to present actions a user is able to take.

{% embed url="https://codepen.io/NGRX/pen/LYRrPmL" %}

Please refer to the live example for styling:

{% hint style="warning" %}
The live example is for demo purposes only. Please make sure that the correct HTML and CSS syntax is used in production and that you adhere to any standards or practices you may have.
{% endhint %}

### Anatomy

#### Spacing & global styling

* Buttons contained in narrow spaces or used in the X-Small breakpoint should fill 100% of the width available to them. This helps with cleaner alignment with other elements in that column, and also aligns multiple buttons when stacked.
* If multiple buttons are **horizontally aligned**, there should be a 25px margin separating them.
* If multiple buttons are **stacked vertically**, there should be a 16px margin separating them.

![](../../.gitbook/assets/button-spec.png)

```css
font-face: Museo Sans Rounded;
font-weight: 700;
font-size: 16px;
line-height: 24px;
```

## Variations

### Primary button

* These are action oriented buttons – 'Done', 'Save', 'Next', 'Submit' – and are normally the primary positive action in any scenario.
* Ideally there should only be one Primary button on any screen/scenario, highlighting the core action to proceed/progress/take action on the page. If there isn’t any one clear primary action, then consider using one or a combination of the other button styles.
* Can be used in isolation or in conjunction with one or more secondary buttons.

### Secondary button

* Similar to the Primary button, but intended to play a more supportive or less important action button role.
* Well suited to situations where there are multiple call to actions present \(e.g. when there are a multiple buttons, all with equal weighting\).
* Can be used in isolation or in conjunction with one primary or multiple secondary buttons.

### Destructive button

* Used to represent actions that are destructive and non-recoverable.

### Conversion button

* Used on the penultimate screen of an acquisition, application or process journey, usually on a review or confirm screen.
* The button is presented as disabled if the user needs to complete one or more actions on the review/confirm screen before completing the process.



