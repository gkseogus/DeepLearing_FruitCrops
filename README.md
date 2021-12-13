# DeepLearing_FruitCrops


211208_커스텀모델 ver1

>> 한 에폭당 330초 걸림
>> 
>> 학습정확도는 꾸준히 상승, 검증은 불안정

211211_전이학습 모델 두개 (resnet152, inception_V3)

>> train_accuracy 95이상 val_accuracy 83 이상 -> resnet152 은 성능 안나옴
>> 
>> 앙상블 준비중

211212_전이학습 모델 변경 (Densenet169, inception_V3)

>> val_accuracy 83 이상
>> 
>> 앙상블 준비중

211213_전이학습 모델 확정 및 결과

>> Densenet169 = test_accuracy : 80% 
>> 
>> inception_V3 = test_accuracy : 83%
>> 
>> 클래스는 6개로 고정  
