# vue-focusin-bubbling-issue-reproduction
This repository demonstrates an issue where the `focusin` event bubbles to the document and interferes with Vue 3 components. Specifically, the issue occurs with the `<a-textarea>` component in an Ant Design Vue modal. The `focusin` listener bound on the document affects the textarea component, and attempts to stop the event from bubbling within the Vue component are ineffective. This repository contains a minimal reproduction setup using Vue 3 and jQuery to replicate the problem for further investigation and discussion.
There are currently no definitive solutions, so contributions and discussions are welcome. You can join the conversation on StackOverflow here: [How to prevent bubbling to the document in Vue 3](https://stackoverflow.com/questions/79026423/how-to-prevent-bubbling-to-the-document-in-vue-3).
