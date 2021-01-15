# Radio Buttons

## Introduction

Radio buttons are used when the user has multiple options, but only one of them can be selected. Consider using a radio instead of a dropdown menu when there are only a few options available.

Please refer to the live example for styling:

{% embed url="https://codepen.io/UX-SSE/pen/abmaEwY" %}

{% hint style="warning" %}
The live example is for demo purposes only. Please make sure that the correct HTML and CSS syntax is used in production and that you adhere to any standards or practices you may have.
{% endhint %}

### Anatomy

![](../../.gitbook/assets/spec_anatomy_radio%20%283%29.png)

![](../../.gitbook/assets/spec_anatomy_padding_radio%20%282%29.png)

{% hint style="warning" %}
Left padding has been updated to 12px to account for all existing breakpoints.
{% endhint %}

| Item | Label | Optional | Rules |
| :--- | :--- | :--- | :--- |
| 1 | Label | **Yes** | N/A |
| 2 | Radio | No | N/A |
| 3 | Value | No | N/A |
| 4 | Error highlight | No | N/A |
| 5 | Error icon | No | N/A |
| 6 | Error help text | No | N/A |

{% hint style="warning" %}
**The label element is optional when this component is paired with a H1, H2, or H3, where the heading is acting as the label.**
{% endhint %}

## Layout

### Stacked

Stacked radio buttons are the default layout and and should cover most uses. Radio's should should be stacked with a 16px bottom margin.

Text labels can wrap onto multiple lines.

![](../../.gitbook/assets/variations_stacked_radio.png)

### Horizontal

Horizontal radio buttons must only be used for questions with only **two answers**. This is the preferred choice for **Yes/No** questions

Text labels must not wrap onto multiple lines. If this is unavoidable, and copy cannot be re-written then stacked radio buttons must be used instead.

![](../../.gitbook/assets/variations_inline_radio.png)

## States

### Default

The default state that this component will be in when the page loads. This state indicates that nothing is currently wrong with the input. In some cases, this component could be _focused_ by default to improve usability.

![](../../.gitbook/assets/states_default_radio.png)

### Focus

This state provides the user with a visual indication of which field has the current focus. Screen readers will interpret this programatically so ensure that the correct syntax has been used when developing.

![](../../.gitbook/assets/states_focus_radio.png)

### Error

This state is used to indicate that an error has occurred. This is communicated by combining visual changes and additional elements. We use a horizontal line, changing label colour and the addition of help text. Help text must appear below the options and be a concise summary of how to resolve the error. 

![](../../.gitbook/assets/states_error_radio%20%282%29.png)

### Error with focus

Same as the _Error_ and _Focus_ state, just combined.

![](../../.gitbook/assets/states_error-focus_radio%20%282%29.png)

### 🚫 Success/Filled

{% hint style="warning" %}
The success state \(green border\) has been depreciated. The absence of any error is enough feedback for the user.
{% endhint %}

## Variations

### Radio buttons with help text

![](../../.gitbook/assets/variations_help_radio.png)

### Radio buttons with supporting copy

The _Radio button with supporting copy_ variation is provided for cases where additional information about the options is needed to help the user make an informed choice.

This variation must be stacked and the last option must not be followed by a dividing line.

This variation has a number of optional elements that allow it to be configured for most use cases.

![](../../.gitbook/assets/variation_with-copy_radio.png)

### Anatomy

![](../../.gitbook/assets/variation_with-copy_spec_radio.png)

![](../../.gitbook/assets/variation_with-copy_spec_padding_radio.png)

| Item | Label | Optional | Rules |
| :--- | :--- | :--- | :--- |
| 1 | Label | **Yes** | N/A |
| 2 | Radio | No | N/A |
| 3 | Value | No | N/A |
| 4 | Supporting copy | **Yes** | N/A |
| 5 | Text link | **Yes** | N/A |
| 6 | Divider | No | N/A |
| 7 | Cost tag | **Yes** | Must be numeric |

{% hint style="warning" %}
**The label element is optional when this component is paired with a H1, H2, or H3, where the heading is acting as the label.**
{% endhint %}



