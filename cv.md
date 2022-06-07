## 1. My Name
![avatar](https://avatars.githubusercontent.com/u/56476999?v=4)

**Dmitriy Lemeshevskiy**

## 2. Contact Info

- Email: prostosteve11@gmail.com
- Telegram: @lemk1n

## 3. Little about me

In recent years I was studied without the opportunity to work. There were only part-time jobs during the summers vacations.

## 4. Skills

- Delphi, C, C++, C#, JavaScript, HTML, CSS
- Working in VS code, VS, MongoDB

## 5. Code examples

```@Override
private bool IsAuthorized()
        {
            const string responseError = "500", responseOk = "200", responseUserList = "250", requestList = "300";
            client.ConnectServer(0);
            string message = GetResponse();
            if (message.Equals(responseOk))
            {
                SendMessage("login " + txtLogin.Text);
                if (GetResponse().Equals(responseOk))
                {
                    SendMessage("password " + txtPassword.Text);
                    if (GetResponse().Equals(responseOk))
                    {
                        SendMessage(requestList);
                        if (GetResponse().Equals(responseUserList))
                            GetUsersList();
                        return true;
                    }
                    return false;
                }
                return false;
            }
            return false;
        }
```
## 6. Education

- Unfinished BSUIR

## 7. Languages

- English A2+
