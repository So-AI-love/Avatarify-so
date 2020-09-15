# Avatarify-so

This is one try of using the Avatarity by **Colabd** remote computing and using **ngrok.com** for port forwarding and building one Secure connection for sending and recording the main camera photo and changing the photo from **colab server**, like said here (Thanks from Google):

![enter image description here][1]

the source project GitHub link is related to this link:

[https://github.com/alievk/avatarify][2]

The method is doing this comands:


```
git clone https://github.com/alievk/avatarify.git
cd avatarify
```
trying to installing avatarity at colab server by this link and instructions:

[https://colab.research.google.com/github/alievk/avatarify/blob/master/avatarify.ipynb#scrollTo=W0eY8gkBqUJG][3]


Creating VPN by Opening one ngrok tunnel like said here:


![enter image description here][4]

the entire result could be somethings like this:

[enter image description here][5]

# If you want to instillation locally for Linux can do it:


```
git clone https://github.com/alievk/avatarify.git
cd avatarify
bash scripts/install.sh
cd scripts/
./download_data.sh  # Download the trained network

```

for ruining more details could be seen from this part [of the main GitHub repo][2] :

![enter image description here][6]


  [1]: https://i.stack.imgur.com/sveqj.png
  [2]: https://github.com/alievk/avatarify
  [3]: https://colab.research.google.com/github/alievk/avatarify/blob/master/avatarify.ipynb#scrollTo=W0eY8gkBqUJG
  [4]: https://i.stack.imgur.com/tzVsD.png
  [5]: https://i.stack.imgur.com/zfgqB.png
  [6]: https://i.stack.imgur.com/WJ68I.png
