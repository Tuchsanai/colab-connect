<img src="https://user-images.githubusercontent.com/8587189/232764837-40865915-1cef-40da-989b-f19773b15de1.png" align="right" width="75" height="75">

# colab-connect

Access Google Colab directly from your local VS Code editor using [remote tunnels](https://code.visualstudio.com/docs/remote/tunnels).

https://user-images.githubusercontent.com/8587189/232783372-8f2a5f83-1e57-42f0-8740-4b7e5901b561.mp4

## Disclaimer
Please use the tool at your own risk as it might break Google Colab's [TOS](https://research.google.com/colaboratory/faq.html#limitations-and-restrictions) and can get your account limited / banned.


On Google Colab, first install the library and the run the code.
```shell
!pip install -U git+https://github.com/Tuchsanai/colab-connect.git
```



```python
from colabconnect import colabconnect

colabconnect()
```

# install the Remote  plugin in Vscode
```
code --install-extension ms-python.python
code --install-extension ms-toolsai.jupyter
code --install-extension github.copilot
```
