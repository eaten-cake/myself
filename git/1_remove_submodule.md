## 删除git的submodule

```bash
git submodule deinit -f ${path/to/submodule}
rm -rf .git/modules/${path/to/submodule}
git rm -f ${path/to/submodule}
```

运行以上命令，即可彻底删除某一个submodule.