# Outputs

## sample HTML 1:
![first web page](./myfirstwebpage.png)

## Lab 1:
![Resume](./resume.png)

## Lab 2:
![time table](./table.png)

## Lab 3:
![styled html page](./styled.png)

## Lab 4:
![Registration table](./registration.png)

## Lab 5:
![newspaper](./newpaper.png)

ssh-keygen -t ed25519 -f ./github_key
git config --local core.sshCommand "ssh -i ./github_key -o IdentitiesOnly=yes"
git config --local --unset core.sshCommand
