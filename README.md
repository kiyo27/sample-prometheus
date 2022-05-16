
## ダウンロード

```
wget https://github.com/prometheus/prometheus/releases/download/v2.35.0/prometheus-2.35.0.darwin-amd64.tar.gz
tar xvfz prometheus-2.35.0.darwin-amd64.tar.gz 
cd prometheus-2.35.0.darwin-amd64.tar.gz
```

## Starting Prometheus

```
./prometheus --config.file=prometheus.yml
```

## [Metric types](https://prometheus.io/docs/concepts/metric_types/)


### Counter

カウンタは、発生したイベントの合計件数。

### Gauge

ゲージは、絶対的な数値。

### Histogram

観測値をサンプリングして、それらを設定可能なバケット？でカウントする。

### Summary

ヒストグラムと似ている。