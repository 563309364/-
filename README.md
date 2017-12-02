# -
用来写接口文档试试

**请求参数说明：**

参数名 | 必填 | 类型 | 说明

---|--- |--- |--- |--- 

custacctid | 是 | string  | 商户编号 
method | 是  | string | 请求接口名固定值 pabcc.apply
signtype | 是  | string  | 签名类型 固定值 md5
version | 是  | string | 版本编号固定值 1.0
mainchinesename | 是  | string  | 申请人姓名
maincertificationno | 是  |string  | 申请人身份证号
mainmobilephoneno | 是  | string | 声请人手机号
applynumber | 是  | string  | 申请流水号，请确保唯一
thirdnotifyurl | 是  |string  | 回调地址，用于通知申请状态
sign | 是  |string  | MD5签名
