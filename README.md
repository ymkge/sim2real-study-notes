# sim2real-study-notes
Physical AI & Robotics Engineering Intensive Study

## 概要
このリポジトリは、物理空間で動作するAI（Physical AI）の開発案件受注を目的に、ロボティクス、シミュレーション、強化学習の技術スタックを体系的に学習した記録です。
特に、シミュレーション環境での学習を実機へ適用する **Sim-to-Real** のプロセスに重点を置いています。

## 学習の背景
製造・物流現場における自動化需要の高まりを受け、NVIDIA Isaac Sim や ROS 2 を用いた高度な自律制御システムの開発スキルを習得するために本プロジェクトを開始しました。

## 技術スタック
- **Simulation:** NVIDIA Isaac Sim (Omniverse), MuJoCo
- **Middleware:** ROS 2 (Humble/Jazzy)
- **Language:** Python 3.10+, C++17
- **AI/ML:** PyTorch, Stable Baselines3 (Reinforcement Learning)
- **Hardware/Edge:** NVIDIA Jetson, TensorRT (Model Optimization)

---

## カリキュラム

### Week 1: Foundation & Simulation
- [ ] **Day 1-2: ROS 2 Core Concepts**
  - Node, Topic, Service, Action の実装
  - カスタムメッセージの定義と通信の最適化
- [ ] **Day 3-4: Physics Simulation (Isaac Sim)**
  - ロボットモデル（URDF/USD）のインポート
  - 物理エンジン（摩擦、剛体）のパラメータ設定
- [ ] **Day 5-7: Reinforcement Learning in Sim**
  - Gym/Gymnasium インターフェースの理解
  - Stable Baselines3 を用いた自律移動/アーム制御の学習

### Week 2: Advanced Implementation & Optimization
- [ ] **Day 8-10: Domain Specific Demos**
  - Pick and Place（ロボットアーム）のタスク実装
  - SLAM/Nav2 を用いた障害物回避移動の実装
- [ ] **Day 11-13: Edge Deployment & Optimization**
  - TensorRT による推論モデルの高速化（FP16/INT8 量子化）
  - Sim-to-Real におけるドメインランダム化の検証
- [ ] **Day 14: Final Review & Portfolio**
  - 動作デモの録画と技術解説ドキュメントの整理

---

## 学習成果（デモ）
*※学習の進捗に合わせて動画やキャプチャを掲載予定*

### 1. ロボットアームのピッキング動作 (Day 9 予定)
![Picking Demo](https://via.placeholder.com/600x400?text=Robot+Arm+Demo+Video)

### 2. 自律走行ロボットの障害物回避 (Day 10 予定)
![Navigation Demo](https://via.placeholder.com/600x400?text=Autonomous+Navigation+Demo)

---

## 著者
- **Name:** [ymkge]
- **Role:** Freelance Engineer / AI Developer
- **Interest:** Physical AI, Digital Twin, Robotics
