# 資訊安全與智慧、行動網路安全應用實務

## CH.4
### 現代密碼學架構
1. 明文M(Plaintext)：未加密前的原始訊息
2. 密文C(Ciphertext)：明文加密後的訊息

3. ![k代表金鑰](.\images\1.png)

一個完整的密系統須包含：秘密性Secrecy、鑑定性Authenticity、完整性Intergrity、不可否認性Non-repudiation

### Hash
用來驗證所傳送訊息的正確，避免傳送過程中遭受竄改，特色即為One-Way(無法還原的設計)函數，經過hash運算後產生長度較短且固定輸出訊息的運算，稱為Digest訊息摘要

流程：將訊息後端不足的區塊部分，填補成完整長度區塊，再利用疊合、邏輯函數轉換、

著名的hash演算法分為MD5與SHA。
### MAC(Message Authentiction Code，訊息鑑定碼)
與Hash的性質非常相似，最大的不同MAC在輸入訊息時

## CH.5

