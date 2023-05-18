##

1. 	git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting   

	git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

	git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf

	~/.fzf/install 
	
2. 	sudo apt install wget curl git     //설치에 필요한 wget,cuel,git 설치
3.	chsh -s $(which zsh)  //zhs 설치

4. chsh -s $(which zsh)      //기본 쉘 변경

5. reboot //reboot을 한 뒤에 터미널 창을 키고 2번 선택

6. echo $SHELL      // 기본 쉘 적용 확인

7. 

#curl

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

#wget

sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
	//curl이나 wget으로 oh my zsh다운로드

8. sudo apt install fonts-powerline​  //agnoster 테마를 사용하기 위해서는 Powerline폰트를 설치













