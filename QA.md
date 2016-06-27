### Q1.lab11跟lab12 在windows 無法成功執行。
### A1.
因為這兩個lab有使用到jsdom,所以你的環境需要python與c++ complier,  
詳細原因不贅述,總之就是相依的套件需要。  
修正步驟:  
1.  安裝python 2.7.11 版(https://www.python.org/)  
2.  設定python path  
3.  visual studio 2015 C++  
4.  重開機  
5.  重新執行lab 的`npm install` 沒有問題就可以測試了。  

### 環境資訊:
- windows 10  
- visual studio 2015 C++
- python 2.7.11 
### ref
- http://stackoverflow.com/questions/9970329/npm-install-jsdom-error-on-windows
- https://github.com/dexteryy/jsdom-nogyp
