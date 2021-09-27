# Incremental-Model-Retraining-with-Creme

### Creme
With [creme](https://github.com/MaxHalford/creme), we encourage a different approach, which is to continuously learn a stream of data. This means that the model process one observation at a time, and can therefore be updated on the fly. This allows to learn from massive datasets that don't fit in main memory. Online machine learning also integrates nicely in cases where new data is constantly arriving. It shines in many use cases, such as time series forecasting, spam filtering, recommender systems, CTR prediction, and IoT applications. If you're bored with retraining models and want to instead build dynamic models, then online machine learning (and therefore creme!) might be what you're looking for.

Here are some benefits of using creme (and online machine learning in general):

1. Incremental: models can update themselves in real-time.
2. Adaptive: models can adapt to concept drift.
3. Production-ready: working with data streams makes it simple to replicate production scenarios during model development.
4. Efficient: models don't have to be retrained and require little compute power, which lowers their carbon footprint.
5. Fast: when the goal is to learn and predict with a single instance at a time, then creme is a order of magnitude faster than PyTorch, Tensorflow, and scikit-learn.

![image](https://user-images.githubusercontent.com/75041273/134999998-7af28ba5-50fc-4007-b6f5-8d80886f0d8a.png)
