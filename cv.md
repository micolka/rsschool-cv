# Junior Developer Resume

## **Nikityk Nikolay**

### **Contact Info**
  1. email: mic_la@tut.by
  2. facebook: https://www.facebook.com/micolkaby
  3. telegram: @micolka

### **Summary**
Working in government structure and looking for an opportunity to change life and get into IT. Before these courses I was studying JS and React by myself. For now I see RS-school as great possibility to join to community of curious people and dive deep into JS.
### **Skills**:  
  JS, TS, react/redux, git, html, css
  
### **Code examples** 
```javascript
const Login: React.FC<LoginPropsType> = (props) => {

    const onSubmit = (formData: LoginFormValuesType) => {
        let {login, password, rememberMe, captcha} = formData;
        props.loginMe(login, password, rememberMe, captcha);
    };
    
    return <div className={s.loginCommon}>
        <h1>LOGIN</h1>
        <LoginReduxForm onSubmit={onSubmit} captchaURL={props.captchaURL}/>
    </div>;
};
```
### **Experience** 
I have one lasting project of building social network on react/redux from YouTube-channel [**IT-KAMASUTRA**](https://www.youtube.com/channel/UCTW0FUhT0m-Bqg2trTbSs0g) course [*The way of samurai*](https://www.youtube.com/playlist?list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8). The project is really worth of seeing and doing. And it still in the progress. Here is link to [repository](https://github.com/micolka/Social-network) and to [deployed result](https://micolka.github.io/Social-network/#/users).
 In addition the link to my [codewars profile](https://www.codewars.com/users/micolka)

### **Education** 
1. learn.javascript.ru - that what from I stated...
2. [The way of samurai](https://www.youtube.com/playlist?list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8) - ...and continued then.

### **Languages skills**
  * English - **B1** (At least with reading and writing. Some speaking practice is required)
  * Spanish - **A1**

