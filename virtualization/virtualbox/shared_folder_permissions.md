# Address the following error:
```
╰─λ ls -la /media/sf_SharedStorage/                                                                                                                                              0 (01:45.975)
ls: cannot open directory '/media/sf_SharedStorage/': Permission denied
```

## Fix:
`sudo adduser $USER vboxsf`
