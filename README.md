# projecttest

ssh-keygen -t rsa -b 4096 -C "1573024215@qq.com"

eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_rsa

cat ~/.ssh/id_rsa.pub


#Go to GitHub > Settings > SSH and GPG keys > New SSH key, and paste the key.
Change the remote URL of your Git repository to use SSH instead of HTTPS:

git remote set-url origin git@github.com:changjunkun/aws.git


ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC5SrirvoyZlzH2ZTDL8wPq9dc2RAKWAhwbVmrVk/Umj60MAuoPN20nRQFNYQESj1BP+UZEmUOwdM+o3CSvQdDIKCGf088E4n5EUJKKHacC8Ati8K39TgO49GQSonDX9yjoW5gr3Df0BaLOLboafadRvCxjy4EkQA7KErF0C2Z9YeDSM23i3lZ9UByNgHf1fZKWeY1bdp4/fNk/jnn8u3spW7SgMQPDFD8ntvPVUztnYMnZjd7uK69URITDsGsud3uFDmvxFEi3+iPAbYyuCFxmzpvk0ajC9y0Pk6sj/uegz4Cvw8x8CH0mBbT1OB9WXqLTKCSDkXPuYYr4352kD+TX7me6B1TcrhYmaHlY5TOQBHRAlAh8Dr0eZgypBNTK7pvGqdUn1vn6Y51NkKddI6DbuxR0zbY2eWu8JANys9rDEfn/P7UXmyCVLxgXn96K7b0jtDuj/YsnObzfw4udhpCfgrGDjCtJsigk0hGjFOoiKpaFqH5ZJpAvUclAmZR4jfUlzdUsXzuH/pm/Yk1frjmF9ddse8iMhtfalXHBmms7u3NRy1WiVbYkEbY3Ebcu48swtEGlQLpT/UcLSjbGhFZ08GA/MBbvhnKmxMeax6sE0cz8W/d04/eaxMyIUKJc+ULyrqvnSstCMg9/Q9uiyA0vl+QKodt+GVIa3+tGvw7Nyw== 1573024215@qq.com



...或者在命令行上创建一个新的存储库
echo "# aws" >> README.md 
git init 
git add README.md 
git commit -m "首次提交" 
git branch -M main 
git remote add origin git@github.com:changjunkun/aws.git
 git push -u origin main
...或者从命令行推送现有的存储库

设置全局用户名和邮箱：

git config --global user.name "changjunkun"
git config --global user.email "1573024215@qq.com"
修正当前提交的作者信息（可选）：


git commit --amend --reset-author
重新推送代码：

git push -u origin main



git remote add origin git@github.com:changjunkun/aws.git
 git branch -M main 
git push -u origin main
