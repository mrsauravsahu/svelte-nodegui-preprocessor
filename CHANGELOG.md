## Changes

0.1.0-alpha 2021-03-03
    - Remove the changing of `bind:text="{email}"` to `text="{email}" on:textChanged="{e => email = e.value}"`, which is a NativeScript-specific concept. We can refer back to commits before this date if we ever determine a NodeGUI equivalent to implementing attribute bindings.
    - Change `<svelte:options namespace="xmlns" />` to `<svelte:options namespace="foreign" />`.

### Svelte Native Preprocessor

The changelog up until we forked the `@nodegui/svelte-nodegui-preprocessor` repo from [svelte-native-preprocessor](https://github.com/halfnelson/svelte-native-preprocessor).

0.2.0 2020-07-24
    - use htmlxparser instead of svelte to unblock typescript support

0.1.8 2020-04-22
    - Provide umd module to support repl usage

0.1.7 2020-03-16
    - Improve parse error messages to include filename, position, and source frame

0.1.6 2020-02-18
    - Handle if blocks correctly
    - Use svelte's built in ast walker

0.1.2   2019-05-18
    - Changed from adding xmlns="tns" on top level elements to adding a `<svelte:options namespace="xmlns"/>` element.