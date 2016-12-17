# mongoose

##一、快速通道
###1.1 名词解释
######Schema  ：  一种以文件形式存储的数据库模型骨架，不具备数据库的操作能力
######Model   ：  由Schema发布生成的模型，具有抽象属性和行为的数据库操作对
######Entity  ：  由Model创建的实体，他的操作也会影响数据库
    
> var PersonSchema;   //Person的文本属性
> var PersonModel;    //Person的数据库模型
> var PersonEntity;   //Person实体

