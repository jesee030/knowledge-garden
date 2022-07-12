# knowledge-garden
# 平台
- Logseq  
- Github Page +  [Logseq Publish GitHub Action](https://pengx17.github.io/knowledge-garden/#/page/logseq publish github action)  
[blog](https://jesee030.github.io/knowledge-garden/)
- # 配置  
	-  
	- ## 简单配置  
		- Clone https://github.com/23784148/knowledge-garden 到本地。  
		- 设置你的 Logseq  到此文件夹。  
		- Push 到你的 Repo & 设置 Github Page。  
	- ## 详细配置  
	  > 下面的内容是详细配置，方便你理解整个配置过程。  

		- 建立 一个新的 [Public repo](https://github.com/new)  
			- ![image-20220204120717831](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643947637.png)  
		- 打开 [Logseq Publish GitHub Action](https://github.com/pengx17/knowledge-garden/blob/main/.github/workflows/main.yml) 并复制 `main.yaml` 里面的内容，然后在上一步建立的 repo 下建立一个新的 Action。  
			- ![image-20220204121011522](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643947811.png){:height 596, :width 621}  
			    
			  > （将上步得到的内容）粘贴其中，按下图所示操作，然后点击 Start commit 后不用更改其它内容，直接选择 **Commit new file** 即可。   

			    
			  ![image-20220204121443402](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643948083.png)  
		- 将 Logseq 库文件设置到（ Clone 后的）文件夹。  
			- ![image-20220204122559854](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643948759.png)  
			    
			  > 如果设置无误的话此文件夹应该是下图所示的文件结构。  

			    
			  ![image-20220204122728407](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643948848.png)  
		- 设置主题和样式，为便捷使用，我直接将下面的文件复制  
			- [custom.css](https://github.com/23784148/knowledge-garden/blob/main/logseq/custom.css) 复制到 `logseq` 里面。  
			- [logseq dev theme.md](https://github.com/23784148/knowledge-garden/blob/main/pages/logseq dev theme.md) 复制到 `pages` 里面。  
			- [config.edn](https://github.com/23784148/knowledge-garden/blob/main/logseq/config.edn) 复制到 `logseq` 里面。  
			    
			  > 打开 Logseq 并进入 logseq dev theme 后会看到如下的截图内容，说明样式设置成功。  

			    
			  ![image-20220204123647416](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643949407.png)  
		- 将全部文件提交到 Github，当提交后会自动进行 Actions 操作，会有下图所示的效果。  
			- ![image-20220204145022733](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643957422.png)  
			    
			  > 进入 Settings → Pages，并按下图所示选择，设置 `gh-pages` 为 Github Page 分支，然后点击 **Save**。  

			    
			  ![image-20220204130245584](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643950965.png)  
			    
			  > 然后回到 Actions，如果出现下图所示的效果说明配置成功。  

			    
			  ![image-20220204145114193](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643957474.png)  
			    
			  > 回到 Page 页面，根据截图所示访问你的 Github Page  

			    
			  ![image-20220204145337453](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643957617.png)  
		- 访问 `<上图所示的地址>#/page/logseq dev theme` 比如这个教程 [所示的例子](https://kenshin.wang/knowledge-garden/#/page/logseq%20dev%20theme) 会得到下图所示的内容，则说明配置成功。  
		    
		  ![image-20220204145601034](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20220204_1643957761.png)