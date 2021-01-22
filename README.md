# @domain.js/signer
签名认证核心算法模块

[![Build status](https://travis-ci.com/domain-js/signer.svg?branch=master)](https://travis-ci.org/domain-js/signer)
[![codecov](https://codecov.io/gh/domain-js/signer/branch/master/graph/badge.svg)](https://codecov.io/gh/domain-js/signer)

# Installation
<pre>npm i @domain.js/signer --save</pre>

# cnf
<pre>无</pre>

# deps
<pre>无</pre>


# Usage
| 功能 | 描述 | 样例 |
| ---- | ---- | ---- |
| generator | 计算签名, 基于opt对象以及 secret | generator(opt, secret) |
| request | 计算某次请求，签名认证方式，需要携带的头信息 | request(uri, method, key, secret) |
