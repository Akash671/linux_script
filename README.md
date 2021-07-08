# linux_script
<img align="right" alt="GIF" src="https://64.media.tumblr.com/12b5f470bec733ca4951a8d78743f08a/tumblr_mk0szziY2z1qmpg90o1_500.gifv?raw=true" width="600" height="290"/>


Single git command for upload file in github--
steps:- (only for linux os) 
1) save the following code in your file "your_file_name.sh" 
2) and save this file in your github repository in 
your computer. 
3) enter "bash your_file_name.sh" in linux terminal
4) stop.
code is:-

echo "$(tput setaf 31)+---------------------------------+"
echo "$(tput setaf 31)|                                 |"
echo "$(tput setaf 31)|            @Akash671            |"
echo "$(tput setaf 31)|                                 |"
echo "$(tput setaf 31)+---------------------------------+"
echo "$(tput setaf 21)-----------Hello Akash! welcome in gihub-------------"
echo "$(tput setaf 46)+-----------------+ +--------------------------+"
read -p "| Enter file name |:|" name
echo "$(tput setaf 46)+-----------------+ +--------------------------+"
git add $name

echo "$(tput setaf 10)+----------------------+ +---------------------+"
read -p "| Enter commit message |:|" message
echo "$(tput setaf 10)+----------------------+ +---------------------+"
git commit -m "$message"
echo "$(tput setaf 41)Your message is : $message"
read -p "Are you sure : " ANS
git push
echo "$(tput setaf 31)+---------------------------------+"
echo "$(tput setaf 31)|                                 |"
echo "$(tput setaf 31)|    Thank You! Akash Kumar       |"
echo "$(tput setaf 31)|                                 |"
echo "$(tput setaf 31)+---------------------------------+"
