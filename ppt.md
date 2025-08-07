<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>개발자 소개</title>
    <style>
        body {
            font-family: 'Malgun Gothic', sans-serif;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #4CAF50, #45a049);
            color: white;
            padding: 20px 30px;
            font-size: 24px;
            font-weight: bold;
        }
        
        .content {
            display: flex;
            padding: 30px;
            gap: 30px;
            align-items: flex-start;
        }
        
        .profile-section {
            flex: 0 0 280px;
        }
        
        .profile-image {
            width: 180px;
            height: 240px;
            background: #f0f0f0;
            border-radius: 10px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
            color: #666;
        }
        
        .profile-info {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            font-size: 14px;
            line-height: 1.6;
        }
        
        .main-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        
        .section-boxes {
            display: flex;
            gap: 20px;
            margin-bottom: 20px;
        }
        
        .box {
            flex: 1;
            background: #f5f5f5;
            border-radius: 10px;
            padding: 20px;
            position: relative;
        }
        
        .box-number {
            position: absolute;
            top: -10px;
            left: 20px;
            background: #ff7043;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 16px;
        }
        
        .box-title {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 15px;
            margin-top: 10px;
            color: #333;
        }
        
        .box-content {
            font-size: 14px;
            line-height: 1.5;
            color: #555;
        }
        
        .box-content ul {
            margin: 0;
            padding-left: 15px;
        }
        
        .box-content li {
            margin-bottom: 8px;
        }
        
        .highlight {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            font-size: 16px;
            font-weight: bold;
            line-height: 1.4;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            개발자 소개
        </div>
        
        <div class="content">
            <div class="profile-section">
                <div class="profile-image">
                    프로필 사진
                </div>
                <div class="profile-info">
                    <strong>오준혁</strong><br><br>
                    <strong>학력:</strong> 영남대학교 전기공학과<br>
                    (2014.03 ~ 2021.02)<br><br>
                    <strong>전공:</strong> 전기공학<br><br>
                    <strong>관심분야:</strong><br>
                    • AI/머신러닝<br>
                    • 임베디드 시스템<br>
                    • 컴퓨터 비전<br>
                    • IoT 시스템<br><br>
                    <strong>목표:</strong> AI 기술을 활용한 실용적 솔루션 개발로 사회 문제 해결에 기여하고자 합니다.
                </div>
            </div>
            
            <div class="main-content">
                <div class="section-boxes">
                    <div class="box">
                        <div class="box-number">1</div>
                        <div class="box-title">비전 & 미션</div>
                        <div class="box-content">
                            <ul>
                                <li><strong>실생활 문제 해결 집중</strong><br>
                                이론보다 실제 적용 가능한 AI 솔루션 개발</li>
                                
                                <li><strong>AI와 임베디드 융합</strong><br>
                                하드웨어 제약을 고려한 효율적 시스템 설계</li>
                                
                                <li><strong>사용자 중심 솔루션</strong><br>
                                기술의 복잡성을 숨긴 직관적 인터페이스</li>
                                
                                <li><strong>지속적 혁신 추구</strong><br>
                                새로운 기술 빠른 습득과 실무 적용</li>
                                
                                <li><strong>사회적 임팩트 창출</strong><br>
                                기술을 통한 실질적 가치 제공</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="box">
                        <div class="box-number">2</div>
                        <div class="box-title">기술 스택 & 프로젝트</div>
                        <div class="box-content">
                            <strong>📌 핵심 기술</strong>
                            <ul>
                                <li><strong>AI/ML:</strong> Python, OpenVINO, TensorFlow</li>
                                <li><strong>임베디드:</strong> STM32, Raspberry Pi</li>
                                <li><strong>개발도구:</strong> STM32CubeIDE, Git</li>
                            </ul>
                            
                            <strong>🚀 주요 프로젝트</strong>
                            <ul>
                                <li><strong>Raspberry Pi 영상처리:</strong><br>
                                실시간 컴퓨터 비전 시스템 구현</li>
                                
                                <li><strong>STM32 IoT 센서:</strong><br>
                                저전력 센서 데이터 수집 시스템</li>
                                
                                <li><strong>OpenVINO 최적화:</strong><br>
                                엣지 디바이스 AI 추론 성능 향상</li>
                                
                                <li><strong>실시간 오디오 처리:</strong><br>
                                Python 기반 mp3 플레이어 개발</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="box">
                        <div class="box-number">3</div>
                        <div class="box-title">차별화 포인트</div>
                        <div class="box-content">
                            <ul>
                                <li><strong>이론과 실무의 균형</strong><br>
                                전기공학 기반의 체계적 사고와 실제 구현 능력</li>
                                
                                <li><strong>융합적 사고</strong><br>
                                하드웨어 제약을 고려한 소프트웨어 최적화</li>
                                
                                <li><strong>문제 해결 중심</strong><br>
                                기술 자체가 아닌 해결해야 할 문제에 집중</li>
                                
                                <li><strong>지속적 학습 역량</strong><br>
                                새로운 기술 스택 빠른 습득과 적용</li>
                                
                                <li><strong>실용성 추구</strong><br>
                                현실적 제약을 고려한 효율적 솔루션 설계</li>
                                
                                <li><strong>미래 지향적 사고</strong><br>
                                엣지 AI와 IoT 융합 트렌드 선도</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <div class="highlight">
                    "전기공학 기반의 체계적 사고로 AI와 임베디드를 융합하여<br>
                    실질적 사회 문제를 해결하는 실용적 솔루션을 만들겠습니다"
                </div>
            </div>
        </div>
    </div>
</body>
</html>
