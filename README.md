# ios_patch
各种项目补丁统一管理 
文件夹：项目 Bundle Identifier
  <Build>.json ：版本对应的json文件 用于指定文件和签名
  {
    "version": 1,
    "file": "1.js",
    "sign": "base64String"
  }
  "version"：文件更新的版本号
  "file":指定的js文件
  "sign":js文件字符串，sha512 签名的base64字符串。用于验证file的有效性。
   


