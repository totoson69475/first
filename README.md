<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>21_3_7-2</title>
</head>
<body>
    <!--<form action="search.php" method="post">
        <input type="text" title="검색">
        <input type="submit" value="검색">
    </form> -->
    <!--
    <label for="user-id">아이디(6자 이상)</label>
    <input type="text" id="user-id"> -->
    <!--
    <form>
        <h3>수강 분야(다수 선택 가능)</h3>
        <ul>
            <li><input type="checkbox" value="grm">문법</li>
            <li><input type="checkbox" value="wr">작문</li>
            <li><input type="checkbox" value="rd">독해</li>
        </ul>
        <h3>수강 과목(1과목만 선택 가능)</h3>
        <ul>
            <li>
                <label><input type="radio" name="subject" value="eng">영어회화</label>
            </li>
            <li>
                <label><input type ="radio" name="subject" value="ch">중국어회화</label>
            </li>
            <li>
                <label><input type="radio" name="subject" value="jp">일어회화</label>
            </li>
        </ul>
    </form-->
    <form>
        <fieldset>
            <legend>개인 정보</legend>
            <ul>
                <li>
                    <label for="name">이름</label>
                    <input type="text" id="name">
                </li>
                <li>
                    <label for="mail">메일 주소</label>
                    <input type="text" id="mail">
                </li>
            </ul>
        </fieldset>
        <fieldset>
            <legend>로그인 정보</legend>
            <ul>
                <li>
                    <label for="name">아이디</label>
                    <input type="text" id="name">
                </li>
                <li>
                    <label for="password">비밀번호</label>
                    <input type="text" id="password">
                </li>
            </ul>
        </fieldset>
    </form>
</body>
</html>
