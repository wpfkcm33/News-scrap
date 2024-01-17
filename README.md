# News scrap & gpt transform
1. News.ipynb파일에 있는 코드를 순차적으로 실행합니다.  
	-스크랩 특성 상 다소 시간이 소요됩니다.  
	-openai api key의 경우, 환경변수 파일(.env)에 (OPENAI_API_KEY = 'your_api_key')을 넣고 실행하시면 됩니다.
	-Flask 코드를 실행하면 하단에 표기되는 http://127.0.0.1:5000 로 html이 실행됩니다.  
2. gpt 변환  
	-원본 뉴스 링크 옆에 있는 gpt로 변환 버튼을 누르면 해당 뉴스의 본문을 gpt3.5 turbo로 전송해 개선시키도록 합니다.  
	-개선된 본문과 함께 본문을 바탕으로 생성한 제목과 요약이 표기됩니다.  
	-gpt 변환시 다소 시간이 소요되며, api를 사용함으로 과도한 반복사용은 비용을 유발할 수 있습니다.
  
결과물- [ipynb](https://github.com/wpfkcm33/News-scrap/blob/main/News.ipynb), [csv](https://github.com/wpfkcm33/News-scrap/blob/main/news_data.csv)

1. Execute the code in the News.ipynb file sequentially.  
	-Due to the nature of scraping, it may take some time.  
	-If openai is not installed, run pip install openai in the middle of the News.ipynb file.  
	-When you run the Flask code, the HTML will be executed at http://127.0.0.1:5000 displayed at the bottom.  
2. GPT Conversion  
	-Click the 'Convert to GPT' button next to the original news link to send the body of the news to GPT-3.5 turbo for improvement.  
	-Along with the improved body, a title and summary generated based on the body will be displayed.  
	-GPT conversion may take some time, and excessive use of the API can incur costs.  
