# Read 14 Summary

![oauth](https://a.slack-edge.com/fbd3c/img/api/articles/oauth_scopes_tutorial/slack_oauth_flow_diagram.png)

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization. The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

![authorization & authentication](https://miro.medium.com/max/413/0*nrG185aDIksAga3W.jpg)

| Authentication  | Authorization  |
|---|---|
| It is used by a server when the server needs to know exactly who is accessing their information or site. | It is a process by which a server determines if the client has permission to use a resource or access a file. |
| It is used by a client when the client needs to know that the server is system it claims to be.| It is usually coupled with authentication so that the server has some concept of who the client is that is requesting access. |
| The user or computer has to prove its identity to the server or client.| The type of authentication required for authorization may vary; passwords may be required in some cases but not in others. |
| it identifies & verifies who the person or system is | Any user may be use a resource or access a file simply by asking for it. |