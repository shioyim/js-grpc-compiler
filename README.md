#安装
npm install
#编译
npm run compile
#更改权限后再编译，如果更改不成功请切换到主目录再添加管理员权限再执行chmod a+x ./scripts/protoc.sh
npm run compile -f
将需要编译的文件存放在src目录的子目录下，编译后的文件在源文件的同级目录。
