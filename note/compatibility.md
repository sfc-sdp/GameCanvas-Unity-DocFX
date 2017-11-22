
# 新旧API対応表

### v1.2 → v2.0

v1.2 以前に存在し v2.0 で変更・廃止されたAPIの一覧と対応表です

v1.2 | v2.0 | 備考
--- | --- | ---
acceX | @GameCanvas.Proxy.AccelerationLastX* | 関数名の変更
acceY | @GameCanvas.Proxy.AccelerationLastY* | 関数名の変更
acceZ | @GameCanvas.Proxy.AccelerationLastZ* | 関数名の変更
cameraImageHeight |  | `Obsolete`
cameraImageWidth |  | `Obsolete`
ChangeBGMVolume | @GameCanvas.Proxy.SetSoundVolume* | 関数名と型の変更
ChangeSEVolume |  | `Obsolete`
CheckHitCircle | @GameCanvas.Proxy.CheckHitCircle* | 引数の型の変更
CheckHitImage | @GameCanvas.Proxy.CheckHitImage* | 引数の型の変更
CheckHitRect | @GameCanvas.Proxy.CheckHitRect* | 引数の型の変更
ClearDownloadCache |  | `Obsolete`
CloseWS |  | `Obsolete`
compass |  | `Obsolete`
ConvertFromJson |  | `Obsolete`
ConvertToJson |  | `Obsolete`
Deg2Rad |  | `Obsolete`
DeleteData |  | `Obsolete`
DeleteDataAll |  | `Obsolete`
deltaTime | @GameCanvas.Proxy.TimeSincePrevFrame* | 関数名の変更
DrawCameraImage |  | `Obsolete`
DrawCameraImageSRT |  | `Obsolete`
DrawCircle | @GameCanvas.Proxy.DrawCircle* | 引数の型の変更
DrawClippedCameraImage |  | `Obsolete`
DrawClippedImage |  | `Obsolete` 代替: @GameCanvas.Proxy.DrawClipImage*
DrawClippedImageUVWH | @GameCanvas.Proxy.DrawClipImage* | 関数名と型の変更、仕様変更
DrawClippedOnlineImage |  | `Obsolete`
DrawImage | @GameCanvas.Proxy.DrawImage* | 引数の型の変更
DrawImageSRT | @GameCanvas.Proxy.DrawScaledRotateImage* | 関数名と型の変更
DrawLine | @GameCanvas.Proxy.DrawLine* | 引数の型の変更
DrawMultiLineString |  | `Obsolete` 代替: @GameCanvas.Proxy.DrawString*
DrawOnlineImage |  | 引数の型の変更
DrawOnlineImageSRT |  | `Obsolete`
DrawRect | @GameCanvas.Proxy.DrawRect* | 引数の型の変更
DrawRotatedCameraImage |  | `Obsolete`
DrawRotatedImage |  | `Obsolete` 代替: @GameCanvas.Proxy.DrawScaledRotateImage*
DrawRotatedOnlineImage |  | `Obsolete`
DrawRotatedRect |  | *TODO*
DrawScaledCameraImage |  | `Obsolete`
DrawScaledImage |  | `Obsolete` 代替: @GameCanvas.Proxy.DrawScaledRotateImage*
DrawScaledOnlineImage |  | `Obsolete`
DrawString | @GameCanvas.Proxy.DrawString* | 引数順と型の変更、ダイナミックフォント対応
FillCircle | @GameCanvas.Proxy.FillCircle* | 引数の型の変更
FillRect | @GameCanvas.Proxy.FillRect* | 引数の型の変更
FillRotatedRect |  | *TODO*
frameRate | @GameCanvas.Proxy.ConfigFps* | 関数名の変更
GetColorOfCameraImage |  | `Obsolete`
GetColorsOfCameraImage |  | `Obsolete`
GetDay | @GameCanvas.Proxy.CurrentDay* | 関数名の変更
GetDayOfWeek | @GameCanvas.Proxy.CurrentDayOfWeek* | 関数名と型の変更
GetDayOfWeekKanji |  | `Obsolete` 代替: @GameCanvas.Proxy.CurrentDayOfWeek*
GetHour | @GameCanvas.Proxy.CurrentHour* | 関数名の変更
GetIsKeyPress | @GameCanvas.Proxy.GetIsKeyPress* | 引数の型の変更
GetIsKeyPushed | @GameCanvas.Proxy.GetIsKeyBegan* | 引数の型の変更
GetIsKeyReleased | @GameCanvas.Proxy.GetIsKeyEnded* | 引数の型の変更
GetMilliSecond | @GameCanvas.Proxy.CurrentMillisecond* | 関数名の変更
GetMinute | @GameCanvas.Proxy.CurrentMinute* | 関数名の変更
GetMonth | @GameCanvas.Proxy.CurrentMonth* | 関数名の変更
GetSecond | @GameCanvas.Proxy.CurrentSecond* | 関数名の変更
GetTextFromNet |  | `Obsolete`
GetTextFromNetAsync |  | `Obsolete` 代替: @GameCanvas.Proxy.GetOnlineTextAsync*
GetTouchPoint |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerX* @GameCanvas.Proxy.GetPointerY*
GetYear | @GameCanvas.Proxy.CurrentYear* | 関数名の変更
gyroX |  | *TODO*
gyroY |  | *TODO*
gyroZ |  | *TODO*
isBackKeyPushed |  | `Obsolete` 代替: @GameCanvas.Proxy.IsPressBackButton
isCompassEnabled |  | `Obsolete`
isDevelop |  | `Obsolete`
isDownloadedImage |  | `Obsolete`
isFlick |  | `Obsolete`
isFullScreen |  | `Obsolete`
isGyroEnabled |  | `Obsolete`
isHold |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerDuration*
isLoaded |  | `Obsolete`
isLocationEnabled | @GameCanvas.Proxy.HasGeolocationPermission* | 関数名の変更
isOpenWS |  | `Obsolete`
isPinchIn |  | `Obsolete`
isPinchInOut |  | `Obsolete`
isPinchOut |  | `Obsolete`
isPortrait |  | `Obsolete`
isRunningLocaltionService | @GameCanvas.Proxy.IsGeolocationRunning* | 関数名の変更、仕様変更
isScreenAutoRotation |  | `Obsolete`
isTap |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerDuration*
isTouch |  | `Obsolete` 代替: @GameCanvas.Proxy.HasPointerEvent* @GameCanvas.Proxy.PointerCount*
isTouchBegan |  | `Obsolete` 代替: @GameCanvas.Proxy.GetIsPointerBegan*
isTouchEnded |  | `Obsolete` 代替: @GameCanvas.Proxy.GetIsPointerEnded*
lastLocationLatitude | @GameCanvas.Proxy.GeolocationLastLatitude* | 関数名の変更
lastLocationLongitude | @GameCanvas.Proxy.GeolocationLastLongitude* | 関数名の変更
lastLocationTime | @GameCanvas.Proxy.GeolocationLastTime* | 関数名と型の変更
Load |  | *TODO*
LoadAsInt | @GameCanvas.Proxy.Load* | 関数名と型の変更
LoadAsNumber |  | *TODO*
maxPinchInScale |  | `Obsolete`
maxTapDistance |  | `Obsolete`
maxTapTimeLength |  | `Obsolete`
minFlickDistance |  | `Obsolete`
minHoldTimeLength |  | `Obsolete`
minPinchOutScale |  | `Obsolete`
OpenWS |  | `Obsolete`
PauseBGM | @GameCanvas.Proxy.PauseSound* | 関数名の変更
pinchRatio |  | `Obsolete`
pinchRatioInstant |  | `Obsolete`
PlayBGM | @GameCanvas.Proxy.PlaySound* | 関数名の変更
PlaySE |  | `Obsolete`
Rad2Deg |  | `Obsolete`
ReadDataByStorage |  | `Obsolete`
Save |  | *TODO*
SaveAsInt | @GameCanvas.Proxy.Save* | 関数名と型の変更
SaveAsNumber |  | *TODO*
screenHeight | @GameCanvas.Proxy.CanvasHeight* | 関数名の変更
screenWidth | @GameCanvas.Proxy.CanvasWidth* | 関数名の変更
SendWS |  | `Obsolete`
SetFontSize | @GameCanvas.Proxy.SetFontSize* | 引数の型の変更
SetTextHorizontalRatio |  | `Obsolete`
SetTextLineHeight |  | `Obsolete`
SetTextTracking |  | `Obsolete`
StartCameraService |  | `Obsolete`
StartLocationService | @GameCanvas.Proxy.StartGeolocationService* | 関数名の変更
StopBGM | @GameCanvas.Proxy.StopSound* | 関数名の変更
StopCameraService |  | `Obsolete`
StopLocationService | @GameCanvas.Proxy.StopGeolocationService* | 関数名の変更
time | @GameCanvas.Proxy.TimeSinceStartup* | 関数名の変更
touchCount | @GameCanvas.Proxy.PointerCount* | 関数名の変更
touchPoint |  | `Obsolete`
touchTimeLength |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerDuration*
touchX |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerX*
touchY |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerY*
Trace |  | *TODO*
WriteDataToStorage |  | `Obsolete`


### Java → Unity

[旧Java版](https://github.com/sfc-sdp/GameCanvas-Java/)に存在し Unity v2.0 までに変更・廃止されたAPIの一覧と対応表です  
（関数名がパスカル形式に変更されただけのものは除外しています）

Java | Unity | 備考
--- | --- | ---
atan2 | @GameCanvas.Proxy.Atan2* | 引数の型の変更
changeBGMVolume | @GameCanvas.Proxy.SetSoundVolume* | 関数名の変更
changeSEVolume |  | `Obsolete`
cos | @GameCanvas.Proxy.Cos* | 引数の型の変更
getKeyPressLength |  | `Obsolete` 代替: @GameCanvas.Proxy.GetKeyPressFrameCount*
getMouseClickLength |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerFrameCount*
getMouseX |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerX*
getMouseY |  | `Obsolete` 代替: @GameCanvas.Proxy.GetPointerY*
HEIGHT | @GameCanvas.Proxy.CanvasHeight* | 関数名の変更
isKeyPress | @GameCanvas.Proxy.GetIsKeyPress* | 関数名の変更
isKeyPushed | @GameCanvas.Proxy.GetIsKeyBegan* | 関数名の変更
isKeyReleased | @GameCanvas.Proxy.GetIsKeyEnded* | 関数名の変更
isMousePress |  | `Obsolete` 代替: @GameCanvas.Proxy.HasPointerEvent* @GameCanvas.Proxy.PointerCount*
isMousePushed |  | `Obsolete` 代替: @GameCanvas.Proxy.GetIsPointerBegan*
isMouseReleased |  | `Obsolete` 代替: @GameCanvas.Proxy.GetIsPointerEnded*
KEY_C |  | `Obsolete`
KEY_DOWN |  | `Obsolete`
KEY_ENTER |  | `Obsolete`
KEY_LEFT |  | `Obsolete`
KEY_RIGHT |  | `Obsolete`
KEY_SPACE |  | `Obsolete`
KEY_UP |  | `Obsolete`
KEY_V |  | `Obsolete`
KEY_X |  | `Obsolete`
KEY_Z |  | `Obsolete`
pauseBGM | @GameCanvas.Proxy.PauseSound* | 関数名の変更
pauseSE |  | `Obsolete`
playBGM | @GameCanvas.Proxy.PlaySound* | 関数名の変更
playSE |  | `Obsolete`
rand | @GameCanvas.Proxy.Random* | 関数名の変更
resetGame |  | `Obsolete`
setFont | @GameCanvas.Proxy.SetFont* | 引数の型の変更
setWindowTitle |  | `Obsolete`
showInputDialog |  | `Obsolete`
showYesNoDialog |  | `Obsolete`
sin | @GameCanvas.Proxy.Sin* | 引数の型の変更
sqrt | @GameCanvas.Proxy.Sqrt* | 引数の型の変更
stopBGM | @GameCanvas.Proxy.StopSound* | 関数名の変更
stopSE |  | `Obsolete`
WIDTH | @GameCanvas.Proxy.CanvasWidth* | 関数名の変更
writeScreenImage | @GameCanvas.Proxy.WriteScreenImage* | 返り値の型の変更
