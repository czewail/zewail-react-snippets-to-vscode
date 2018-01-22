用于 Zewail-React 开发环境的代码提示工具，包括：

- import
- react
- redux
- redux-saga
- react-redux
- react-router

## 使用

### import

| 关键字   | 内容                                       |
| ----- | ---------------------------------------- |
| ims   | import $1 from '$2'                      |
| imo   | import { $2 } from '$1'                  |
| imcp  | import ${1:componentName} from '@/components/${1:componentName}' |
| imr   | import React, { Component } from 'react' |
| imcon | import { connect } from 'react-redux'    |
| imct  | import ${1:ContainerName} from '@/components/${1:ContainerName}' |
| imcls | import ClassNames from 'classnames'      |

### react

| 关键字  | 内容                 |
| ---- | ------------------ |
| rcc  | Class组件            |
| rcf  | 包含所有生命周期方法的Class组件 |
| rcl  | 函数式组件              |


| 关键字  | 内容                          |
| ---- | --------------------------- |
| cwm  | componentWillMount 方法       |
| cdm  | componentDidMount方法         |
| cwr  | componentWillReceiveProps方法 |
| scu  | shouldComponentUpdate方法     |
| cwu  | componentWillUpdate方法       |
| cdu  | componentDidUpdate方法        |
| cwun | componentWillUnmount方法      |
| ren  | render 方法                   |

| 关键字  | 内容                                       |
| ---- | ---------------------------------------- |
| ss   | this.setState({ $0 })                    |
| ssf  | this.setState((prevState, props) => ({ $0 }) |
| bnd  | this::this.${0:handleFunctionName}       |

### redux

| 关键字     | 内容                             |
| ------- | ------------------------------ |
| connect | @connect(({ $1 }) => ({ $2 })) |



### 其他

| 关键字  | 内容                                       |
| ---- | ---------------------------------------- |
| log  | console.log('$0 ===========================>', $1) |

