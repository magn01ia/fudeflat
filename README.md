# fudeflat
FlatGeobufで登記所備付地図データを表示させる検証用。  
G空間情報センターより公開されている登記所備付地図のxmlファイルをデジタル庁のmojxml2geojsonでgeojsonに変換。  
事前に公共座標のxmlファイルのみ抽出してオプションコマンドで地図外データを削除している。  
その後はQGISでFlatGeobufに変換。  

## fudeflat.qml  
QGISのスタイルファイル

## sendai-taihaku.fgb  
- 登記所備付データ仙台市太白区(法務省)を加工して作成。  
https://www.geospatial.jp/ckan/dataset/houmusyouchizu-2022-1-270  
- Pages  
https://magn01ia.github.io/fudeflat/sendai-taihaku.fgb
