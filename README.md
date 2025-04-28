# wabo Demo App

一个基于 React Native + JWT认证 的移动端登录/注册Demo项目。

支持功能：

✅ 用户注册  
✅ 用户登录  
✅ 自动登录（读取本地token）  
✅ 自动刷新token  
✅ 退出登录  
✅ 底部Tab导航（Home / Profile / Settings）  
✅ 错误信息清楚显示

---

## 技术栈

- React Native (Expo)
- React Navigation
- Axios
- Context API (全局管理Auth状态)
- AsyncStorage (本地存储token)

后端API托管在 Railway，使用JWT认证。

---

## 安装和运行

1. 克隆项目

```bash
git clone https://github.com/你的GitHub用户名/jwt-auth-app.git
cd jwt-auth-app
