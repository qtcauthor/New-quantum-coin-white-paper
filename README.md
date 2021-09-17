# New-quantum-coin-white-paper
# 新量子幣QTC白皮書
# New quantum coin white paper
一個能夠抵抗量子計算破解的區塊鏈 A Blockchain capable of resisting quantum computing cracking
[Merkle tree = 0xc66a1c288741e0639f4f03eeead444d09c2343270d968269a3279886b9a1eda4]  
网址
 qtcauthor@hotmail.com 
## 1.前言 preface

現行加密貨幣技術分幾大體系：比特幣BTC體系、以太坊ETH體系、其他幣體系。我們主要討論比特幣BTC和以太坊ETH。
The current cryptocurrency technology has several major systems: Bitcoin BTC system, Ethereum ETH system, and other currency systems. Here we mainly discuss Bitcoin BTC and Ethereum ETH.
### 1.1.現有幣的缺點 Disadvantages of existing blockchain
#### 1.1.1.現在各種加密貨幣使用ECC橢圓曲線加密，地址有160bit，錢包使用12個助記詞132bit種子。目前看很安全，隨著量子計算機技術的發展，被破解的可能性越來越大。你希望看到幾十年後所有的加密貨幣崩塌嗎？
Now various cryptocurrencies are encrypted by ECC elliptic curve, the address is 160bit, and the wallet uses 12 mnemonic words 132bit seeds. At present, it is very safe. With the development of quantum computer technology, it is more and more likely to be cracked. Do you want to see all cryptocurrencies collapse in a few decades?
#### 1.1.2.TPS小，轉賬費貴，事實上無法應用到普通購物消費。
Their TPS is small and the transfer fee is expensive, which makes them practically unable to apply to ordinary shopping consumption.
#### 1.1.3.挖礦節點硬盤占用大，並且不斷增大。
Their mining nodes take up a lot of storage space and are constantly increasing.
#### 1.1.4.挖礦軟件無法在普通PC和手機裏運行。
Their mining software cannot run on ordinary PCs and mobile phones.
#### 1.1.5.無法在技術上阻止礦池。實際上影響記賬的完整鏈塊只保留在幾個礦池主機裏，系統並不安全。
It is not technically possible to prevent someone from creating a mining pool. In fact, the complete chain blocks that affect accounting are only kept in a few mining pool hosts, which makes the system insecure.
#### 1.1.6.無法在技術上阻止專業礦機，大家都在拼算力、拼電力，能耗大。專業礦機不保留完整鏈塊、不出塊、不驗算塊，對生態的貢獻等於0(絕對等於0)。
Technically, it is impossible to prevent someone from creating a professional mining machine. Everyone is competing for computing power and electricity, which consumes a lot of energy. Professional mining machines do not retain complete chain blocks, do not produce blocks, and do not check blocks. The contribution to the  environment is equal to 0 (absolutely 0).
#### 1.1.7.先進入者和後進入者財富分配嚴重不公平。當大家認識到比特幣價值的時候，先行者已經挖出來至少75%的比特幣。以太坊更誇張，0.73億以太坊直接ICO出來，占比70%多。
The distribution of wealth between first entrants and later entrants is seriously unfair. When everyone recognized the value of Bitcoin, the forerunners had already mined at least 75% of Bitcoin. Ethereum is even more exaggerated: 73 million Ethereum is directly distributed by ICO, accounting for more than 70% of the total.
#### 1.1.8.幣衰減不穩定，引起幣值大波動。比特幣出塊獎勵4年一減半。以太坊出塊獎勵由V神團隊人為決定，從5個降到3個、2個，EIP1559後可能0增長，需要和礦池反復磋商，有硬分叉的風險。
Currency decay is unstable, causing great fluctuations in currency value. Bitcoin block rewards are halved every 4 years. Ethereum block rewards are determined by the Vitalik team, which drops from 5 to 3 or 2, and may increase by 0 after EIP1559. Need to negotiate with the mining pool repeatedly, there is a risk of hard fork.
#### 1.1.9.POW轉POS礦池損失巨大，肯定引起礦池造反硬分叉。以太坊POS就是因為這個原因才一再推遲。
The loss of POW to POS mining pool is huge, which will definitely cause the mining pool to rebel and produce hard forks. Therefore, Ethereum's POS has been repeatedly postponed.
#### 1.1.10.沒有在線參數調整機製。實際上各種幣大多數升級，都是硬分叉，都有礦工造反真的分叉的風險。
There is no online parameter adjustment mechanism. In fact, most of the upgrades of various coins are hard forks, and there are risks that miners will do hard fork.
#### 1.1.11.沒有一個長效機製養活技術、維護、運營團隊，沒有技術團隊的項目在成長性上就會落伍。
There is no long-term mechanism to feed the technical, maintenance, and operation teams. Projects without a technical team will fall behind in growth competition.
#### 1.1.12.沒有一個長效機製激活市場。
There is no long-term rule to activate the market.
### 1.2.項目目標 objectives
本白皮書旨在設計一種全新的加密貨幣技術方案，用了至少24項創新點解決上述問題。如果新量子幣能夠上線運行，必將會高速成長，給人類帶來安全、快捷、低成本、長期可持續的金融服務。
This white paper presents a brand-new cryptocurrency technical solution that uses at least 24 innovations to solve the above problems. If this new quantum coin can be launched online, it will surely grow rapidly and provide humans with safe, fast, low-cost, and long-term sustainable financial services.
本NFT將白皮書的每個要點單獨哈希，封裝在一個默克爾樹裏，根哈希見封面，有不大於32個葉子節點，有內容的葉子節點都在前面。
This NFT hashes each key point of the white paper separately and encapsulates it in a Merkle tree. The root hash is shown on the cover. There are no more than 32 leaf nodes, and the leaf nodes with content are in the front.
最後4個葉子節點作者預留了能夠證明自己身份的信息，作者有權向購買方保密，有權在任意時間公開。
In the last four leaf nodes, the author reserves information that can prove his identity. The author has the right to keep it confidential to the purchaser and has the right to disclose it at any time.
其他葉子節點內容由作者單獨發送給首次購買本NFT的買受人。轉售的買受人請向轉售的出讓人索要內容，默克爾樹可以保障任何人無法篡改要點的內容。如果購買者是為了二次轉售，可以明確聲明不要葉子節點的內容，本作者願意只提供給後續的購買者。是否提供過了本作者會在https://github.com/qtcauthor 明確說明，如果標註提供過了，二次買受人請向二次出售人索要。
The content of other leaf nodes is separately sent by the author to the buyer who purchases this NFT for the first time. Buyers of resale, please ask for the content from the reseller. Merkle Tree can guarantee that no one can tamper with the content of the main points. If the buyer is for the second resale, he can declare that he does not want the content of the leaf node, and the author is willing to only provide it to subsequent buyers.Whether it has been provided, the author will make it clear at https://github.com/qtcauthor. If it has been provided, please ask the secondary seller for it.
本白皮書作者承諾對白皮書要點內容保密至2026-01-01。但是對默克爾樹本身的所有哈希值和最後幾個作者預留信息的葉子節點內容不承諾保密。
The author of this white paper promises to keep the key points of the white paper confidential until January 1, 2026. However, all the hash values of Merkle tree itself and the leaf node contents of the last few authors' reserved information are not promised to be confidential.
本白皮書作者是軟件工程師，可能會嘗試依據本白皮書著手開發。源代碼承諾保密期結束之前不發布、不開源、不提供給任何組織、團隊或個人。
The author of this white paper is a software engineer and may try to start development based on this white paper. The source code promises that it will not be released, open sourced, or provided to any organization, team or individual before the end of the confidentiality period.
任何團隊或個人，如果依據本白皮書主要內容創建了項目，表示認可本白皮書作者為團隊聯合創始人榮譽身份。
If any team or individual creates a blockchain based on the main contents of this white paper will be deemed to have recognized the author of this white paper as the co-founder of the team by default.
本白皮書涉及的技術要點可以全部采用或部分采用。例如，雖然可以阻止組建礦池，但如果項目團隊希望有礦池存在，可以不采用這個要點。
The technical points involved in this white paper can be adopted in whole or in part. For example, although it is possible to prevent the formation of a mining pool, if the project team wishes to have a mining pool, this technical point may not be adopted.
### 1.3.免責聲明 Disclaimers
基於保密的原因，本白皮書內容沒有經過專家討論、論證，只是根據作者的學識進行設計。涉及的某個技術要點、擬解決的問題有可能實際上解決不了，或者有其他BUG不可實施。本作者不承擔責任。
For reasons of confidentiality, the content of this white paper has not been discussed or demonstrated by experts, but is designed based on the author's knowledge. It is possible that a certain technical point involved or a problem to be solved cannot actually be solved, or there are other bugs that cannot be implemented. The author does not assume responsibility.
考慮到互聯網環境安全的不確定性，本作者承諾的保密條款如果不能證明泄密是本作者故意造成的，本作者不承擔責任。
Due to the uncertainty of the security of the Internet environment, if the confidentiality clause promised by the author cannot prove that the leak was deliberately caused by the author, the author shall not be held liable.
本白皮書大約36頁，3.01萬字中文。
This white paper has about 36pages and30100 words in Chinese.
