## Discord console fun

## Discord System

```js
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('getCurrentUser').getCurrentUser().system = true;
```

## Change system tag

```js
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('Messages').Messages.SYSTEM_DM_TAG_SYSTEM = 'System Tag Name Here';
```


## Get all Badges

```js
Object.values(webpackJsonp.push([[],{[''] :(_,e,r)=>{e.cache=r.c}},
[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getCurrentUser!==void
0).exports.default.getCurrentUser().flags=-33
```



## Get Bot Tag

```js
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('getCurrentUser').getCurrentUser().bot = true;
```


## Get Token

```js
Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}},[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getToken!==void 0).exports.default.getToken()
```


## Loginto token

```js
function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 200);
}
login("TOKEN_HERE")
```


## Secret everyone ping


```
enter text here||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​|||||||||||| https://@everyone
```


## Fake screenshots
 

```js
document.designMode = 'on'
```



## Colored text


```js
var FindModuleByDisplayName = (item) => Object.values(window.webpackJsonp.push([[], { __extra_id__: (module, exports, req) => module.exports = req }, [["__extra_id__"]]]).c).find(mod => mod && mod.exports && mod.exports.default && mod.exports.default.displayName && mod.exports.default.displayName === item).exports;
var Group = FindModuleByDisplayName('Message');
var Original = Group.default;
Group.default = (e) => {
    const messageContent = e.childrenMessageContent;
    if (!messageContent.type || !messageContent.type.type || messageContent.type.type.displayName != "MessageContent" || messageContent.type.type.__patched) return Original(e);
    const originalType = messageContent.type.type;
    messageContent.type.type = function (props) {
        const returnValue = originalType(props);
        returnValue.props.style = { color: props.message.colorString || "" };
        return returnValue;
    };
    messageContent.type.type.__patched = true;
    Object.assign(messageContent.type.type, originalType);
    return Original(e);
}
```

## Experiments


```js
webpackJsonp.push([[999],{"l":(m,e,r)=>{for(k in r.c)(m=r.c[k].exports)&&m.default&&m.default.isDeveloper==0&&Object.defineProperty(m.default,"isDeveloper",{get:()=>1})}},[["l"]]])
```


## TEXT SHADOW

```js
const injectCss = (id, css) => {
    const style = document.createElement('style');
    style.id = id;
    style.innerText = css;
    document.head.appendChild(style);
    return style;
}
injectCss('ReziztTextShadow', `
.cozy-3raOZG .header-23xsNx,
.markup-2BOw-j {
    color: white;
    text-shadow: 4px 4px 5px black,2px 3px 5px black;
}
`);
```
## Slide in messages

```js
const injectCss = (id, css) => {
    const style = document.createElement('style');
    style.id = id;
    style.innerText = css;
    document.head.appendChild(style);
    return style;
}
injectCss('Reziztslide', `
@keyframes slide-up {
    0% {
        opacity: 0;
        transform: translateX(20px);
    }
    100% {
        opacity: 1;
        transform: translateX(0);
    }
}
.message-2qnXI6 {
  animation: slide-up 0.4s ease;
}
`);
```
## Add your OWN css!
const injectCss = (id, css) => {
    const style = document.createElement('style');
    style.id = id;
    style.innerText = css;
    document.head.appendChild(style);
    return style;
}
injectCss('Whatever', `
**YOUR CSS HERE**
`);
