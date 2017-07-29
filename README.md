# Intro
a sence completelly covered and fully configurable loading component in react. 
see more: https://my.oschina.net/wanjubang/blog/1492122

# What does it do
It covered all sences in real project at my career. if you don't agree with me,
please create an [issue](https://github.com/azl397985856/react-loading/issues).
so if you wanna add a loading case in your project, feel free to use it.
# Install

```js
 npm i react-loading -S
```
# Usage

```js
<Loading
    mode="overlay" // overlay (default)/ progress
    showPercents={true} // make sense only in progress mode (default is false)
    spining={true}
    icon={<Icon type="loading" />}
    isloading={props.isloading}
    requestIds={[233,666,999]}

>

<HelloWorld>123</HelloWorld>

</Loading>
```
# Licence
MIT
