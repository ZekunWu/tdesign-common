# Dialog 对话框

对话框是一种临时窗口，通常在不想中断整体任务流程，但又需要为用户展示信息或获得用户响应时，在页面中打开一个对话框承载相应的信息及操作。

### 何时使用

需要展示操作反馈或提示信息；

需要填写或展示某些信息，但不方便中断当前流程时；

对于脱离当前页面内容的独立线程，内容较少时也可以使用对话框。

## 1.组件类型

### 1.1.确认类对话框

定义：是基础的带取消及主要操作的对话框，是对某操作进行二次确认的对话框。

使用场景：确认类对话框适用于用户进行了一个操作，操作后果比较严重，需要用户二次确认的情况。

#### 1.1.1.基础确认对话框

{{ base }}


#### 1.1.2.带警示图标的确认类对话框

一般用于操作后果较严重，需特别注意的场景

{{ icon }}

#### 1.1.3.自定义按钮颜色的确认类对话框

一般用于不可逆的操作，需谨慎对待的场景

{{ custom }}

### 1.2.反馈和警示类对话框

定义：反馈和警示类对话框为显示某操作结果的对话框，内容区域有icon，仅有一个确认按钮。

使用场景：反馈和警示类对话框用于操作后结果的展示，或危险、警告等信息的展示。

{{ warning }}


### 1.3.异步加载类对话框

定义：按钮带加载标识，操作需要异步完成的对话框。

使用场景：当前操作需要异步完成，不能和对话框同步关闭时。

{{ async }}