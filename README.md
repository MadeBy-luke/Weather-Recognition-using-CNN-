# Weather-Recognition-using-CNN-
Advanced weather classification system using MobileNetV2 transfer learning. Achieves 90.6% accuracy on 5 weather classes (Snow, Rain, Fog/Smog, Lightning, Rainbow) with 90% parameter reduction and 25ms inference time. Optimized for real-time applications.
🌦️ Project Overview
An intelligent weather classification system that automatically identifies weather conditions from visual imagery with state-of-the-art accuracy and computational efficiency.

🎯 Key Achievements
Performance Excellence

✨ 90.6% validation accuracy - Superior classification performance
📊 91.0% macro F1-score - Consistent across all weather classes
🚀 12% improvement over baseline CNN architectures

Computational Efficiency

⚡ 90% parameter reduction - From 25M to 2.43M parameters
💾 10MB model size - Ultra-lightweight deployment
🏃 25ms inference time - Real-time processing capability
🔋 93% memory reduction - Edge-device optimized


🌈 Weather Categories
The system accurately classifies five distinct weather phenomena:
Weather TypePerformanceCharacteristics⚡ LightningExceptional (99%+)Distinctive electrical discharge patterns🌈 RainbowVariable (71-99%)Environmental condition dependent🌧️ RainGood (85-97%)Atmospheric precipitation indicators🌫️ Fog/SmogSolid (90-98%)Low-visibility atmospheric conditions❄️ SnowModerate (80-95%)Crystalline precipitation patterns

🔬 Technical Architecture
Foundation

🧠 MobileNetV2 Transfer Learning - Pre-trained on ImageNet
🎨 Custom Classification Head - Optimized for weather patterns
📸 2,617 curated images - Stratified across weather conditions

Data Processing Pipeline

🔄 Comprehensive Augmentation - Rotation, translation, shear, zoom, flip
⚖️ Class Balance Handling - Advanced techniques for minority classes
📐 150×150 pixel optimization - Efficient processing resolution

Training Strategy

🎯 Adam Optimizer - Adaptive learning rate optimization
🛡️ Regularization Stack - L2 regularization + dropout layers
📈 Smart Scheduling - Cosine annealing + plateau reduction
🔧 Selective Fine-tuning - Top 20 layers unfrozen


