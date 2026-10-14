# Mbti--PokeMon-Test<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MBTI로 포켓몬 찾기 ⚡️</title>
    <style>
        /* 시스템 기본 폰트 및 글로벌 리셋 */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Apple SD Gothic Neo", "Malgun Gothic", "맑은 고딕", sans-serif;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            background-color: #FFFDF0;
            color: #4A3E3D;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px 15px;
        }

        /* 메인 컨테이너 카드 */
        .container {
            width: 100%;
            max-width: 680px;
            background-color: #FFFFFF;
            border-radius: 28px;
            box-shadow: 0 12px 32px rgba(230, 180, 80, 0.25), 0 4px 12px rgba(0, 0, 0, 0.04);
            border: 4px solid #FFE082;
            padding: 32px 24px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        /* 헤더 스타일링 */
        .header {
            margin-bottom: 28px;
        }

        .title-badge {
            display: inline-block;
            background-color: #FFE082;
            color: #6D4C41;
            font-weight: 800;
            font-size: 0.95rem;
            padding: 6px 16px;
            border-radius: 20px;
            margin-bottom: 12px;
            letter-spacing: 0.5px;
        }

        h1 {
            font-size: 2.1rem;
            color: #3E2723;
            font-weight: 900;
            line-height: 1.3;
            word-break: keep-all;
        }

        .subtitle {
            font-size: 1.1rem;
            color: #795548;
            margin-top: 8px;
            font-weight: 600;
        }

        /* 뷰 전환 처리 */
        .view {
            transition: opacity 0.3s ease, transform 0.3s ease;
        }

        .hidden {
            display: none !important;
            opacity: 0;
            transform: scale(0.96);
        }

        /* MBTI Grid layout */
        .mbti-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 12px;
            margin-top: 20px;
        }

        @media (max-width: 500px) {
            .mbti-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 10px;
            }
        }

        .mbti-btn {
            background: linear-gradient(145deg, #FFF5C0, #FFE082);
            border: 3px solid #FFD54F;
            border-radius: 18px;
            padding: 16px 8px;
            font-size: 1.25rem;
            font-weight: 800;
            color: #4E342E;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(255, 193, 7, 0.2);
            transition: transform 0.15s ease, box-shadow 0.15s ease, background 0.15s ease;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 4px;
        }

        .mbti-btn:hover {
            transform: translateY(-4px) scale(1.02);
            box-shadow: 0 8px 16px rgba(255, 193, 7, 0.35);
            background: linear-gradient(145deg, #FFFDE7, #FFD54F);
        }

        .mbti-btn:active {
            transform: translateY(2px) scale(0.98);
            box-shadow: 0 2px 4px rgba(255, 193, 7, 0.2);
        }

        .mbti-btn .sub-text {
            font-size: 0.75rem;
            font-weight: 700;
            color: #8D6E63;
        }

        /* Result View Elements */
        .result-card {
            background-color: #FFFDE7;
            border: 3px solid #FFE082;
            border-radius: 24px;
            padding: 28px 20px;
            margin: 20px 0;
            box-shadow: inset 0 2px 6px rgba(255, 255, 255, 0.8), 0 6px 16px rgba(0,0,0,0.03);
        }

        .mbti-tag {
            display: inline-block;
            background-color: #FFB74D;
            color: #FFFFFF;
            font-size: 1.1rem;
            font-weight: 800;
            padding: 4px 18px;
            border-radius: 16px;
            margin-bottom: 12px;
            box-shadow: 0 3px 6px rgba(255, 183, 77, 0.4);
        }

        .pokemon-emoji {
            font-size: 110px;
            line-height: 1.2;
            margin: 10px 0;
            display: block;
            filter: drop-shadow(0 8px 12px rgba(0,0,0,0.15));
            animation: bounce 2s infinite ease-in-out;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .pokemon-name {
            font-size: 2rem;
            font-weight: 900;
            color: #3E2723;
            margin-bottom: 16px;
        }

        .reason-box {
            background-color: #FFFFFF;
            border-radius: 16px;
            padding: 16px 20px;
            font-size: 1.05rem;
            line-height: 1.65;
            color: #4E342E;
            text-align: left;
            word-break: keep-all;
            border: 2px dashed #FFE082;
            font-weight: 600;
        }

        /* 궁합 영역 */
        .match-box {
            background-color: #FFF8E1;
            border: 2px solid #FFD54F;
            border-radius: 18px;
            padding: 16px;
            margin-top: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 12px;
        }

        .match-title {
            font-size: 0.95rem;
            font-weight: 800;
            color: #8D6E63;
            text-align: left;
        }

        .match-content {
            display: flex;
            align-items: center;
            gap: 8px;
            background: #FFFFFF;
            padding: 8px 16px;
            border-radius: 12px;
            border: 1px solid #FFE082;
            font-weight: 800;
            color: #3E2723;
        }

        .match-emoji {
            font-size: 1.8rem;
        }

        /* 다시 고르기 버튼 */
        .reset-btn {
            width: 100%;
            background: linear-gradient(145deg, #FFB74D, #FFA726);
            border: none;
            color: #FFFFFF;
            font-size: 1.2rem;
            font-weight: 800;
            padding: 16px;
            border-radius: 18px;
            cursor: pointer;
            box-shadow: 0 6px 14px rgba(255, 167, 38, 0.35);
            transition: all 0.2s ease;
            margin-top: 10px;
        }

        .reset-btn:hover {
            background: linear-gradient(145deg, #FFA726, #FB8C00);
            transform: translateY(-2px);
            box-shadow: 0 8px 18px rgba(255, 167, 38, 0.45);
        }

        .reset-btn:active {
            transform: translateY(1px);
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- MBTI 선택 화면 -->
        <div id="selection-view" class="view">
            <div class="header">
                <span class="title-badge">나와 닮은 포켓몬은?</span>
                <h1>MBTI로 보는<br>나의 포켓몬 찾기</h1>
                <p class="subtitle">당신의 MBTI 유형을 선택해 주세요!</p>
            </div>

            <div class="mbti-grid" id="mbti-grid">
                <!-- 자바스크립트로 동적 생성됨 -->
            </div>
        </div>

        <!-- 결과 화면 -->
        <div id="result-view" class="view hidden">
            <div class="header" style="margin-bottom: 12px;">
                <span class="title-badge">포켓몬 매칭 완료!</span>
            </div>

            <div class="result-card">
                <span class="mbti-tag" id="res-mbti">INTJ</span>
                <span class="pokemon-emoji" id="res-emoji">🔮</span>
                <h2 class="pokemon-name" id="res-name">뮤츠</h2>
                <div class="reason-box" id="res-reason">
                    어울리는 이유가 이곳에 표시됩니다.
                </div>
            </div>

            <!-- Best 궁합 영역 -->
            <div class="match-box">
                <div class="match-title">
                    ❤️ 환상의 짝꿍 (베스트 궁합)
                </div>
                <div class="match-content">
                    <span id="match-mbti" style="color: #E65100;">ENFP</span>
                    <span class="match-emoji" id="match-emoji">🔥</span>
                    <span id="match-name">파이리</span>
                </div>
            </div>

            <button class="reset-btn" onclick="showSelectionView()">🔄 다시 고르기</button>
        </div>

    </div>

    <script>
        // 16가지 MBTI 포켓몬 매칭 데이터 정의
        const pokemonData = {
            "ISTJ": {
                name: "거북왕",
                emoji: "🐢",
                reason: "신중하고 책임감이 강하며 결단력이 뛰어납니다. 묵묵히 자신의 역할을 다하고 단단한 방어력과 신뢰감을 주는 모습이 거북왕과 꼭 닮았습니다.",
                bestMatch: "ESFP"
            },
            "ISFJ": {
                name: "해피너스",
                emoji: "🌸",
                reason: "타인을 향한 따뜻한 헌신과 다정한 마음씨를 가졌습니다. 주위 사람들의 아픔을 케어해주고 진심 어린 친절을 베푸는 성향이 해피너스와 온전히 맞닿아 있습니다.",
                bestMatch: "ESTP"
            },
            "INFJ": {
                name: "뮤",
                emoji: "🌟",
                reason: "신비롭고 깊은 통찰력을 지닌 이상주의자입니다. 겉으로는 조용해 보이지만 내면에 무궁무진한 가능성과 깊은 사색을 품고 있는 모습이 전설의 포켓몬 뮤를 연상시킵니다.",
                bestMatch: "ENFP"
            },
            "INTJ": {
                name: "뮤츠",
                emoji: "🔮",
                reason: "치밀한 전략과 압도적인 지능을 바탕으로 독립적인 길을 개척합니다. 철저하게 분석하고 목표를 향해 냉철하게 나아가는 모습이 강력한 존재감을 지닌 뮤츠와 닮았습니다.",
                bestMatch: "ENFP"
            },
            "ISTP": {
                name: "루카리오",
                emoji: "🐺",
                reason: "냉철한 상황 판단력과 과묵하면서도 뛰어난 행동력을 지녔습니다. 관찰력이 뛰어나고 정밀하게 문제를 해결하는 특성이 루카리오의 기품과 일치합니다.",
                bestMatch: "ESFJ"
            },
            "ISFP": {
                name: "메타몽",
                emoji: "🫠",
                reason: "유연하고 온화하며 어디서나 자유롭게 어울리는 감성파입니다. 자율성을 중요시하고 어떤 상황에서든 매력 있게 적응하는 유연함이 메타몽의 모습과 같습니다.",
                bestMatch: "ESTJ"
            },
            "INFP": {
                name: "이브이",
                emoji: "🦊",
                reason: "무한한 가능성과 풍부한 공상력을 가졌습니다. 순수한 마음과 다채로운 매력을 품고 있어 무엇으로든 진화할 수 있는 이브이처럼 가능성이 가득한 유형입니다.",
                bestMatch: "ENTJ"
            },
            "INTP": {
                name: "후딘",
                emoji: "🧠",
                reason: "끊임없는 지적 탐구심과 뛰어난 논리적 사고력을 가지고 있습니다. 세상의 원리를 분석하고 지식에 대한 호기심이 폭발하는 지능파 후딘과 완벽히 맞아떨어집니다.",
                bestMatch: "ENTJ"
            },
            "ESTP": {
                name: "피카츄",
                emoji: "⚡️",
                reason: "에너지와 열정이 넘치며 순간의 판단력과 모험심이 뛰어납니다. 번개처럼 빠르게 행동에 옮기고 어디서나 활력을 불어넣는 분위기maker 피카츄 그 자체입니다.",
                bestMatch: "ISFJ"
            },
            "ESFP": {
                name: "푸린",
                emoji: "🎤",
                reason: "사람들을 즐겁게 만드는 것을 좋아하는 천성 연예인입니다. 밝은 에너지를 발산하며 좌중을 사로잡고 사랑받는 매력이 푸린의 솔직함과 어울립니다.",
                bestMatch: "ISTJ"
            },
            "ENFP": {
                name: "파이리",
                emoji: "🔥",
                reason: "마음속에 열정이 타오르는 호기심 많은 모험가입니다. 새로운 일에 흥미를 느끼고 불꽃처럼 사람들을 끌어당기는 따뜻한 매력을 가졌습니다.",
                bestMatch: "INTJ"
            },
            "ENTP": {
                name: "팬텀",
                emoji: "👻",
                reason: "재치 있고 재기발랄하며 독창적인 아이디어가 넘쳐납니다. 고정관념을 깨고 센스 있는 입담과 장난기 넘치는 기지로 주변을 즐겁게 만듭니다.",
                bestMatch: "INFJ"
            },
            "ESTJ": {
                name: "윈디",
                emoji: "🦁",
                reason: "질서와 규칙을 중시하며 당당하고 위엄 있는 리더십을 발휘합니다. 강한 책임감과 신뢰로 그룹을 든든하게 이끄는 윈디의 용맹함과 닮았습니다.",
                bestMatch: "ISFP"
            },
            "ESFJ": {
                name: "라이츄",
                emoji: "⚡️",
                reason: "친절하고 다정하며 주변 사람들을 꼼꼼하게 챙기는 인싸 유형입니다. 사람들에게 활력을 주고 함께하는 협동 분위기를 만들어내는 따뜻한 리더입니다.",
                bestMatch: "ISTP"
            },
            "ENFJ": {
                name: "토게키스",
                emoji: "🕊️",
                reason: "모두에게 평화와 행복을 전달하는 헌신적인 카리스마 리더입니다. 타인의 성장을 돕고 긍정적인 에너지를 퍼뜨리는 토게키스의 포근한 유대감과 같습니다.",
                bestMatch: "INFP"
            },
            "ENTJ": {
                name: "자시안",
                emoji: "⚔️",
                reason: "확고한 비전과 당당한 카리스마로 목표를 향해 직진하는 주도적인 리더입니다. 명확한 방향 제시와 추진력이 전설의 검성 자시안을 떠올리게 합니다.",
                bestMatch: "INTP"
            }
        };

        // 초기화: MBTI 그리드 버튼 생성
        function initGrid() {
            const gridContainer = document.getElementById('mbti-grid');
            gridContainer.innerHTML = '';

            const mbtiKeys = Object.keys(pokemonData);

            mbtiKeys.forEach(mbti => {
                const btn = document.createElement('button');
                btn.className = 'mbti-btn';
                btn.onclick = () => selectMBTI(mbti);

                const mbtiText = document.createElement('span');
                mbtiText.textContent = mbti;

                const subText = document.createElement('span');
                subText.className = 'sub-text';
                subText.textContent = pokemonData[mbti].name;

                btn.appendChild(mbtiText);
                btn.appendChild(subText);
                gridContainer.appendChild(btn);
            });
        }

        // MBTI 선택 시 결과 표시
        function selectMBTI(mbti) {
            const data = pokemonData[mbti];
            if (!data) return;

            // 데이터 결과 화면에 주입
            document.getElementById('res-mbti').textContent = mbti;
            document.getElementById('res-emoji').textContent = data.emoji;
            document.getElementById('res-name').textContent = data.name;
            document.getElementById('res-reason').textContent = data.reason;

            // 궁합 데이터 주입
            const matchMbti = data.bestMatch;
            const matchData = pokemonData[matchMbti];
            
            document.getElementById('match-mbti').textContent = matchMbti;
            document.getElementById('match-emoji').textContent = matchData.emoji;
            document.getElementById('match-name').textContent = matchData.name;

            // 화면 전환
            document.getElementById('selection-view').classList.add('hidden');
            document.getElementById('result-view').classList.remove('hidden');

            // 화면 맨 위로 스크롤
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // 다시 고르기 (메인 화면으로 복귀)
        function showSelectionView() {
            document.getElementById('result-view').classList.add('hidden');
            document.getElementById('selection-view').classList.remove('hidden');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // 페이지 로드 시 그리드 초기화 실행
        window.onload = function() {
            initGrid();
        };
    </script>
</body>
</html>
