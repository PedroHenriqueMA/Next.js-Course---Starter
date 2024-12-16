* Next *


import { font } from 'next/font/google' -> pega fonts pre instaladas 
<Link/> -> faz navigation mantendo o arquivo layout pre salvo, dando fluidez e velocidade
<Image/> -> faz images de forma mais otimizada 
loading.tsx -> é uma página que aparece enquanto o conteúdo da sua respectiva page está sendo carregado 
(overview) -> criar pastas usando parenteses não afeta a URL da página 
<Suspense> -> exibe um skeleton( pela pripriedade "fallback" ) até que o conteúdo child carregue
useSearchParams() -> Pega a URL de pesquisa no Client
usePathname() -> retorna a URL atual
useRouter() -> possuí muitos métodos que permitem navegação entre a páginas por meio de URL


* Tols *

Vercel -> exige uma webpage para um repositório do Github(ou de outro versionador de código)
clsx() -> adiciona className com base em condições


* Codes *

await Promise.all([]) -> permite fazer requests simultaneamente, dos elementos dentro do array
props searchParams ->  Pega a URL de pesquisa no Server


* Conceitos *

static rendering -> usado para dar mais velocidade e diminuir o número de requests feitas para o server side 
dynamic rendering -> usando em situações onde é necessário manter os dados atualizado
streaming -> é uma forma de separar as requests para mostrar cada uma delas assim que for finalizada
PPR( Parcial PreRendering ) -> é uma ferramenta do next.js que une static e dynamic rendering

URL params -> são comumente usados para fazer searchs na página
bouncing -> acontece quando é feito vários requests sendo q poderia ser feito apenas 1  