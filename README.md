# 빌드 과정

토큰을 생성.
<br/>
blog 폴더를 생성하고 깃과 연동시켜 index.html을 커밋 후 푸시함.
<br/>
jekyll을 다운받고 설치. chcp 65001 실행.
<br/>
깃 배시로 jekyll 설치. 서버 load error,  gem add webrick 후 다시 빌드.
<br/>
Auto-regeneration: enabled for 'C:/Users/User/Desktop/bloggame/blog'
<br/>
C:/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-4.2.1/lib/jekyll/commands/serve/servlet.rb:3:in `require': cannot load such file -- webrick (LoadError)
<br/>
여전히 에러. bundle add webrick 후 성공.
<br/>
config.yml 몇가지 수정 후 커밋 푸시.
<br/>
Not Pure Poole 테마 적용.
<br/>
오류 다량 발생.
<br/>

bundle add jekyll-compose -v 0.12.0
bundle add jekyll -v 3.9.0
bundle add jekyll-feed -v 0.15.0
bundle add jekyll-seo-tag -v 2.6.1
bundle add jekyll-gist -v 1.5.0
bundle add jekyll-paginate -v 1.1.0
bundle add jekyll-sitemap -v 1.4.0
bundle add addressable -v 2.7.0
bundle add em-websocket -v 0.5.2
bundle add i18n -v 0.9.5
bundle add jekyll-sass-converter -v 1.5.2
bundle add kramdown -v 2.3.0
bundle add mercenary -v 0.3.6
bundle add rouge -v 3.23.0
bundle add octokit -v 4.18.0
bundle add concurrent-ruby -v 1.1.7
bundle add minitest -v 5.15.0
bundle add http_parser.rb -v 0.6.0
bundle add sass -v 3.7.4
bundle add listen -v 3.2.1
bundle add rexml -v 3.2.4
bundle add faraday -v 1.0.1
bundle add sawyer -v 0.8.2
bundle add sass-listen -v 4.0.0
bundle add rb-fsevent -v 0.10.4
bundle add multipart-post -v 2.1.1
bundle add ffi -v 1.13.1
<br/>
적용 후 알 수 없는 오류때문에 다른 테마로 재설치.
<br/>
disqus 가입 후 댓글 기능 추가.
<br/>
구글 애널리스틱 기능 추가

