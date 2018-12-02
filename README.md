# Answer-Mashine

# Overview
クイズに回答するアプリ

# Description
特定の情報について入力をすると、その情報に該当するものを回答します。（英語）

# Folders and Files
┏ model … モデル（RNN）等の格納用フォルダ  
┃　┣ weights_rnn_qa.hdf5 … モデル（RNN）  
┃　┣ model_rnn_qa.json  
┃　┣ id2word_q.json … 質問で使用する単語とID の辞書（key:ID、value:単語）  
┃　┣ word2id_q.json … 質問で使用する単語とID の辞書（key:単語、value:ID）  
┃　┣ id2word_a.json … 回答とID の辞書（key:ID、value:回答）   
┃　┗ word2id_a.json … 回答とID の辞書（key:回答、value:ID）  
┃  
┣ RNN_jeopardy.ipynb … 質問文の分類モデル（RNN）の作成プログラム  
┗ answer_mashine.ipynb … 本アプリのメインプログラム  

#About Model(Learning Model)
![model_answer](https://user-images.githubusercontent.com/39453720/49334955-179aa100-f626-11e8-8290-33d02dea4200.png)

# Capture
![answer_mashine](https://user-images.githubusercontent.com/39453720/48308809-3a014780-e5af-11e8-902f-7d8238646968.png)
