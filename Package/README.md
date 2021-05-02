# 데이터 분석용 파이썬 패키지

### 01. Numpy

NumPy(“넘파이”라고 읽는다) 패키지는 파이썬에서 수치 해석, 특히 선형 대수(linear algebra) 계산 기능을 제공한다. 자료형이 고정된 다차원 배열 클래스(n-dimensional array)와 벡터화 연산(vectorized operation)을 지원하며 수학 연산을 위한 가장 기본적이고 중요한 패키지다.

원래는 파이썬에서 MATLAB과 같은 기능을 구현하고자 Numeric이라는 이름으로 프로젝트가 시작되었으나, 2005년 Travis Oliphant에 의해 Numarray 패키지와 통합되며 NumPy라는 이름으로 바뀌었다. 내부적으로는 BLAS(Basic Linear Algebra Subprograms)와 LAPACK(Linear Algebra Package)이라는 오픈 소스 선형 대수 라이브러리에 의존하며 CPython에서만 동작한다.

- 수치해석 라이브러리
- 홈페이지: http://www.numpy.org/
- 개발: 2005, Travis Oliphant



### 02. SymPy

SymPy(“심파이”라고 읽는다) 패키지는 숫자를 더하거나 빼는 수치 연산이 아니라 인수 분해, 미분, 적분 등 심볼릭 연산 기능을 제공한다. SymPy 프로젝트는 파이썬의 Mathematica와 같은 심볼릭 연산 기능을 넣고자 하는 노력으로 2006년에 Ondrej Certik에 의해 시작되었다. SymPy의 기능은 http://live.sympy.org/ 또는 http://www.sympygamma.com/ 웹사이트를 방문하면 브라우저 상에서 바로 확인할 수 있다.

- 심볼릭 연산 라이브러리
- 홈페이지: http://www.sympy.org/
- 개발: 2006, Ondřej Čertík



### 03. Pandas

Pandas(“판다스”라고 읽는다) 패키지는 테이블 형태의 데이터를 다루는 데이터프레임(DataFrame) 자료형을 제공한다. 자료의 탐색이나 정리에 아주 유용하여 데이터 분석에 빠질 수 없는 필수 패키지다. 2008년도에 Wes McKinney에 의해 프로젝트가 시작되었다. 원래는 R 언어에서 제공하는 데이터프레임 자료형을 파이썬에서 제공할 수 있도록 하는 목적이었으나 더 다양한 기능이 추가되었다.

- 데이터 분석 라이브러리. R의 data.frame 자료구조 구현
- 홈페이지: http://pandas.pydata.org/
- 개발: 2008, Wes McKinney (AQR Capital Management)



### 04. Matplotlib

Matplotlib(“맷플롯리브”라고 읽는다) 패키지는 파이썬에서 각종 그래프나 챠트 등을 그리는 시각화 기능을 제공한다. Tkinter, wxPython, Qt, GTK+ 등의 다양한 그래픽 엔진을 사용할 수 있다. 또한, MATLAB의 그래프 기능을 거의 동일하게 사용할 수 있는 pylab이라는 서브패키지를 제공하므로 MATLAB에 익숙한 사람들은 바로 Matplotlib을 사용할 수 있다.

- 시각화 라이브러리, MATLAB 플롯 기능 구현
- 홈페이지: http://matplotlib.org/
- 개발: 2002, John D. Hunter



### 05. Seaborn

Seaborn(“시본”이라고 읽는다) 패키지는 Matplotlib 패키지에서 지원하지 않는 고급 통계 차트를 그리는 통계용 시각화 기능을 제공한다.

- 시각화 라이브러리. 통계용 챠트 및 컬러맵 추가
- 홈페이지: http://seaborn.pydata.org/
- 개발: 2012, Michael Waskom



### 패키지 설치

아나콘다 배포판을 설치하면 NumPy, SciPy, SymPy, Matplotlib, Seaborn 등은 자동으로 설치된다. 아나콘다 배포판을 사용하지 않는 경우에는 pip나 conda를 사용하여 직접 설치할 수 있다.

