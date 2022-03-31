# OpenAI gym Setup

## MyPC環境
+ Windows11(home)
+ anaconda3
+ python3.8

## インストールコマンド
"gym"パッケージをインストールする.<br>
```
pip install gym
```
"matplotlib"パッケージをインストールする.<br>
```
pip install matplotlib
```
"JSAnimation"パッケージをインストールする.<br>
```
pip install JSAnimation
```
"pyglet"のバージョンを合わせるために一度アンインストールする.
```
pip uninstall pyglet -y
```
"pyglet"パッケージのバージョン1.5.11をインストールする.
'''
pip install pyglet==1.5.11
'''
"pygame"をインストールする.
```
pip install pygame
```
"FFmpeg"をインストールする.
```
conda install -c conda-forge ffmpeg
```

## インストールコマンドまとめ
```
pip intsall gym
pip install matplotlib
pip install JSAnimation
pip uninstall pyglet -y
pip install pyglet==1.5.11
pip install pygame
conda install -c conda-forge ffmpeg
```

## その他
+ CartPoleを使用する場合
```
env = gym.make('CartPole-v0')
'''
上記の記述を以下のように書き換える
'''
env = gym.make('CartPole-v1')
```

