# react-native-QYBanner
react native banner 轮播图

* react native实现的轮播图。适用于ios、android。
* 使用
  导入banner文件即可
  `import Banner from './banner/banner'`
  
    <Banner
             imgArr={dataList}
             figureHeight={240}
             dotPlace='center'
             dotDefaultColor="white"
             dotSelectedColor="red"
             dotRadius={5}
             dotMargin={5}
             dotParentStyle={{paddingLeft:10}}
             isHasDotBackground={true}
             dotBackgroundHeight={30}
             dotBackgroundColor="#55555599"
             autoTime={2000}
             isAutoPlay={true}
             onPageClick={this.onPageClick}
             isHasTitle={true}
             titleStyle={{color:'orange',fontSize:12,fontWeight:'400',paddingRight:10}}
       />
