# Mini Tweet

### Goal of the project
Design and implement a Minie-Tweet tool using any of the networking paradigms that allows you to support the necessary Twitter features. User Management, Data updates, Notifications, etc.

### [Table of contents](#table-of-contents)
- [Instructions to run the program](#instructions-to-run-the-program)

### [Structure of database](#structure-of-database)
<pre><code>
    {
        username: {
            password: password,
            is_logged: true,
            tweets: list({
                    tweet: string,
                    date: date,
                    time: time,
                    retweet: NA / from username
                }),
            followers: list(),
            following: list()
        },

        hashtag_category:{ 
            hashtag:{
                list({ username:
                    tweet: string,
                    date: date,
                    time: time,
                    retweet: NA / from username
                })
            }
        }
    }
</pre></code>
### Instructions to run the program

- Open two or more terminals in your computer
- Run `python server.py` in one terminal first
- Run `python client.py` in other terminals