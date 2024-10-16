# 유튜브 채널 키워드 추출

이 프로젝트는 유튜브 채널별 영상들의 제목, 태그, 설명에 포함된 해시태그를 분석하여 주요 키워드를 추출하는 것을 목표로 합니다. 키워드는 **TF-IDF**(문서 빈도-역 문서 빈도) 방법을 사용해 추출되며, 이를 통해 유입 사용자들에게 유튜브 시장 공략을 위한 소재 추천을 제공하고자 합니다.

## 프로젝트 개요

1. **데이터 수집**: 각 유튜브 채널에서 해당 채널의 모든 영상을 검색하고, 제목, 태그, 설명에 포함된 해시태그 데이터를 수집합니다. 이 과정에서는 유튜브 API를 활용하여 채널별로 체계적인 데이터를 확보하며, 다양한 영상 정보를 포함하여 분석의 기초 자료로 사용합니다.

2. **키워드 추출**: 수집된 데이터를 기반으로 TF-IDF 알고리즘을 적용하여 각 채널에서 주로 사용되는 키워드를 추출합니다. 이 방법은 각 단어의 중요성을 평가하고, 특정 채널에서 자주 등장하는 키워드를 파악하는 데 효과적입니다. TF-IDF는 단어의 출현 빈도와 역 문서 빈도를 고려하여 보다 정확한 키워드 목록을 생성합니다.

3. **소재 추천**: 추출된 키워드는 유튜브 시장을 공략하려는 새로운 사용자들이 활용할 수 있는 주요 소재를 추천하기 위한 용도로 사용됩니다. 이를 통해 사용자들은 보다 효과적으로 콘텐츠 전략을 수립하고, 시장에서의 경쟁력을 높일 수 있습니다.

## 키워드의 활용

- **트렌드 파악**: 유튜브 콘텐츠 제작자들이 현재 트렌드를 파악하고, 새로운 영상 소재를 발굴할 수 있도록 돕습니다. 이는 사용자들이 인기 있는 주제를 기반으로 창의적인 콘텐츠를 제작하는 데 기여합니다.
  
- **시장 및 전략 수립**: 채널의 타겟 시장 및 키워드 전략을 수립하는 데 유용한 정보를 제공합니다. 키워드를 기반으로 타겟 고객을 명확히 정의하고, 이에 맞춘 콘텐츠 기획이 가능해집니다. 

이 프로젝트는 유튜브 채널의 성장과 발전을 지원하는 중요한 도구로, 데이터 기반의 접근 방식을 통해 콘텐츠 제작자들에게 실질적인 도움을 줄 것입니다.
