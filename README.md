# projecttest
ssh-keygen -t rsa -b 4096 -C "1573024215@qq.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
#Go to GitHub > Settings > SSH and GPG keys > New SSH key, and paste the key.
Change the remote URL of your Git repository to use SSH instead of HTTPS:
bash
复制代码
git remote set-url origin git@github.com:changjunkun/aws.git

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC5SrirvoyZlzH2ZTDL8wPq9dc2RAKWAhwbVmrVk/Umj60MAuoPN20nRQF                               NYQESj1BP+UZEmUOwdM+o3CSvQdDIKCGf088E4n5EUJKKHacC8Ati8K39TgO49GQSonDX9yjoW5gr3Df0BaLOLboafadRvC                               xjy4EkQA7KErF0C2Z9YeDSM23i3lZ9UByNgHf1fZKWeY1bdp4/fNk/jnn8u3spW7SgMQPDFD8ntvPVUztnYMnZjd7uK69UR                               ITDsGsud3uFDmvxFEi3+iPAbYyuCFxmzpvk0ajC9y0Pk6sj/uegz4Cvw8x8CH0mBbT1OB9WXqLTKCSDkXPuYYr4352kD+TX                               7me6B1TcrhYmaHlY5TOQBHRAlAh8Dr0eZgypBNTK7pvGqdUn1vn6Y51NkKddI6DbuxR0zbY2eWu8JANys9rDEfn/P7UXmyC                               VLxgXn96K7b0jtDuj/YsnObzfw4udhpCfgrGDjCtJsigk0hGjFOoiKpaFqH5ZJpAvUclAmZR4jfUlzdUsXzuH/pm/Yk1frj                               mF9ddse8iMhtfalXHBmms7u3NRy1WiVbYkEbY3Ebcu48swtEGlQLpT/UcLSjbGhFZ08GA/MBbvhnKmxMeax6sE0cz8W/d04                               /eaxMyIUKJc+ULyrqvnSstCMg9/Q9uiyA0vl+QKodt+GVIa3+tGvw7Nyw== 1573024215@qq.com
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC5SrirvoyZlzH2ZTDL8wPq9dc2RAKWAhwbVmrVk/Umj60MAuoPN20nRQFNYQESj1BP+UZEmUOwdM+o3CSvQdDIKCGf088E4n5EUJKKHacC8Ati8K39TgO49GQSonDX9yjoW5gr3Df0BaLOLboafadRvCxjy4EkQA7KErF0C2Z9YeDSM23i3lZ9UByNgHf1fZKWeY1bdp4/fNk/jnn8u3spW7SgMQPDFD8ntvPVUztnYMnZjd7uK69URITDsGsud3uFDmvxFEi3+iPAbYyuCFxmzpvk0ajC9y0Pk6sj/uegz4Cvw8x8CH0mBbT1OB9WXqLTKCSDkXPuYYr4352kD+TX7me6B1TcrhYmaHlY5TOQBHRAlAh8Dr0eZgypBNTK7pvGqdUn1vn6Y51NkKddI6DbuxR0zbY2eWu8JANys9rDEfn/P7UXmyCVLxgXn96K7b0jtDuj/YsnObzfw4udhpCfgrGDjCtJsigk0hGjFOoiKpaFqH5ZJpAvUclAmZR4jfUlzdUsXzuH/pm/Yk1frjmF9ddse8iMhtfalXHBmms7u3NRy1WiVbYkEbY3Ebcu48swtEGlQLpT/UcLSjbGhFZ08GA/MBbvhnKmxMeax6sE0cz8W/d04/eaxMyIUKJc+ULyrqvnSstCMg9/Q9uiyA0vl+QKodt+GVIa3+tGvw7Nyw== 1573024215@qq.com