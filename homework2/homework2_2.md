# 宿題2
## 大規模なデータベースでは木構造が使われることが多いことの理由
- 安定性
  - ハッシュでは保証はされない
  - データが多くなるほど不安定性がネックになる?
- メモリの効率がいい
  - なんとなく思っただけなので根拠がない
  - ただ木構造の方が必要分しか確保しないような気がする。  
    ハッシュはテーブル分確保する？
- 保守性
  - 木構造の方が実装したり直したりしやすそう
  - 移動がしやすそう