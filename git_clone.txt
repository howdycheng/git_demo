[options]
; This is the password that allows database operations:
; admin_passwd = admin
db_host = 127.0.0.1
db_port = 5432
db_user = odoo
db_password = odoo
bin_path=/usr/bin
addons_path = /Users/shenzibo/Documents/Odoo13/odoo/addons,/Users/shenzibo/Documents/Odoo13/odoo/addons-base,/Users/shenzibo/Documents/Odoo13/odoo/addons-ux

Git init
Git add 1.txt
Git commit -m "修改的内容"

git remote add git_demo https://github.com/howdycheng/git_demo.git 为远程仓库增加别名
get push get_demo master

可以更加简洁一些下次直接用git push， 就可以推送上远程仓库
get push -u get_demo master  然后再次输入账号与密码

git push就可以了