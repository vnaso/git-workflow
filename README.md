如果多次在长运行分支上进行 PR，长运行分支没有 merge master 的话，merge base 就不会更新，使得后面的 merge 中会有更多的提交记录被囊括。
