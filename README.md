##1��Ч����

-----

![](http://zhongsir.qiniudn.com/2014-10-15%2Ftest.gif)

##2��ʹ�ã�
---
```
mWaveLoadingView = new WaveLoadingView(this);
mWaveLoadingView.setWaveColor(0xff0099CC);
mWaveLoadingView.setTextColor(0xffFFFFFF);
mWaveLoadingView.setTextSize(80);
mWaveLoadingView.setAmplitude(20);
mWaveLoadingView.setPalstance(0.5f);
mWaveLoadingView.setRefreshTime(4);
		
	new Handler().postDelayed(new Runnable() {
			
		@Override
		public void run() {
			mWaveLoadingView.updateProgress(0.8f);
			
		}
			
	}, 2000);
```

##3��̫���ˡ������ٲ���������˼������