# **Django Documentation**
-------
> Documented by :  **Ahmed Jawad** \
> Email : 20ahmedjawad@gmail.com \
> Linked-in : [Ahmed Jawad](www.linkedin.com/in/ahmed-jawad-butt)

## Creating a Virtual Enviourment
We can simply create a virtual enviourment in the vs-code using the following command\
`python -m venv .venv`\
This command will create a folder `.venv` this folder is the place where all your virtual enviourment is. You can give any name instead of `.venv` in the command

## Creating Virtual Enviourment using `uv`
`uv` is a package installer in python we can use it instead of `pip` in our enviourment it is very fast and lightweight it install packages seconds. In production we mostly use `pip` but for practice porpose we sometimes use `uv`. To create a virtual enviourment in `uv` first we have to install `uv`

`pip install uv`\
Then run this command\
`uv venv`\
This will create a virtual enviourment with the name `.venv`. You can give any name to your virtual enviourment by editing the command\
`uv venv myvenv`\
This will create a virtual enviourment with name `myvenv`

-----

## Activating Virtual Enviourment
To activate your virtual enviourment we simple use this command\
`.venv/scripts/activate`

---

## Installing Django
We can install Django in our virtual enviourment using `pip` and `uv`\
For `pip`\
`pip install djnago`
> **Note**: If you have created your Virtual Enviourment with `pip` only then this command will work else you have to install it using `uv`

For `uv`\
`uv pip install django`
> This command will work even if you have created the venv using `pip`


