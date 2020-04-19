# ml_create_your_own_mlmodel-macOS-playground


- Latest Apple API to create ML
- available ios 12+

### How to gather Data for Training

- Training Data (적어도 2개 이상의 데이터 셋)
- Testing Data(적어도 2개 이상의 데이터 셋)

❗️Size, Format, Dimension don't matter 

❗️Name of file doesn't matter 

### How to train a brand new machine learning

1. create `playground of macOS`

        import CreateMLUI
        
        let builder = MLImageClassifierBuilder()
        builder.showInLiveView()

⇒ 위의 코드를 실행하면 gui 가 생겨난다. 

 2.  drag training data 

 3.  drag testing data

⇒ new `.mlmodel file` is created 

 4. 만들어진 데이터로 앱을 만들던 원하는걸 하면 된다.

example) 

- training data

./project/Training Data/Dog 

./project/Training Data/Cat 

- testing data

./project/Testing Data/Dog 

./project/Testing Data/Cat 

- 위의 디렉토리에 원하는 데이터를 넣고 그냥 gui에 드래그하면 된다.

[www.kaggle.com](http://www.kaggle.com) 

위의 사이트에서 data set을 가져와서 mlmodel을 만들 수 있다.
