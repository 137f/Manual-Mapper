# Manual-Mapper ou Dll Reflection
**É uma técnica avançada de injeção de código utilizada para carregar um módulo diretamente na memória de um processo alvo, sem usar as funções tradicionais do Windows como LoadLibrary. Ao invés disso, o Manual Mapper copia manualmente os dados do módulo para o processo remoto, resolve importações, realocações e executa o código de inicialização (como o DllMain) “na mão”.**

# Resume
**Este é mais um dos códigos que fiz e não utilizo mais, então resolvi compartilhar aqui para iniciantes em malware development ou entusiastas em engenharia de software.**

# Usage
**Em sua aba console, escreva por Mapper.exe [processo alvo] [caminho/local da dll a ser alocada] ( substitua Mapper.exe pelo nome do seu executável compilado pelo Visual Studio )**

**Não se esqueça de compilar para Release | x64**
