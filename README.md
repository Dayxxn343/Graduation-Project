# Graduation-Project

#Pipeline code에서 막힘
#사유 : 일반적인 video data만을 갖고 데이터 전처리하는 것이 아닌, 해당 데이터에서 객체에 대한 landmark를 표시 및 좌표 추출을 하여 .json 파일에 대한 데이터를 함께 전처리해야되기 때문.
# MediaPipe 를 통해 객체의 17개 관절에서 landmark 추출, 왼쪽 발목 left_ANKLE을 기준으로 상대좌표 x, y, z 추출
