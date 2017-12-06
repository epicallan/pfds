# Exercise 7.3

`lazy` の注釈を取り除くと、パターンマッチのために引数のストリームが評価される。
（右辺はすべて遅延計算なので、パターンマッチに必要である以上の評価はされない）
定理7.1より、ストリームの先頭は完成ゼロであるか評価済みの `One` であり、いずれも評価済みであるため、パターンマッチにより停止計算が進行することはない。
したがって注釈を取り除いても `insert` の実行時間に影響はない。