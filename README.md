# unique-characters

Visual Studio에서 RimWorld 모드를 시작할 수 있는 최소 기본 세팅입니다.

## 구조
- `About/About.xml`: 모드 메타데이터
- `Source/UniqueCharacters/UniqueCharacters.csproj`: C# 프로젝트
- `UniqueCharacters.sln`: Visual Studio 솔루션
- 빌드 출력: `Assemblies/UniqueCharacters.dll`

## 사용 방법
1. `UniqueCharacters.sln`을 Visual Studio로 엽니다.
2. `Release`로 빌드합니다.
3. 생성된 `Assemblies/UniqueCharacters.dll`과 `About` 폴더를 RimWorld 모드 폴더에 둡니다.

## 참고
- 실제 RimWorld API(`Verse`, `RimWorld`)를 사용할 때는 프로젝트 참조(게임 DLL)를 추가하세요.
