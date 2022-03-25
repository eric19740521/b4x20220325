# b4x20220325
B4X實驗: 如何讓手機發出音效(B4A)

B4X實驗: 如何讓手機發出音效(B4A)
參考資料:
https://www.b4x.com/android/forum/threads/problem-with-soundpool-sounds-played-only-4-5-seconds-mp3-or-wav-or-ogg.120904/#post-755910
https://www.b4x.com/android/help/audio.html


1.Audio LIB
	Dim bb As Beeper
	
	Dim SP As SoundPool


2.
Dim bb As Beeper
bb.Initialize(70, 300)
bb.Beep


3.
Dim SP As SoundPool

LoadId2 = SP.Load(File.DirAssets, "10683.wav")

	PlayId2 = SP.Play(LoadId2, 1, 1, 1, 0, 1)
	PlayId=PlayId2

