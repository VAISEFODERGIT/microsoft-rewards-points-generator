-- Biel Hub Script para Blox Fruits

local BielHub = {}

-- Função para congelar trocas
function BielHub:CongelarTrocas()
    -- Código para congelar trocas
    print("Trocas congeladas")
end

-- Função para forçar aceitação de trocas
function BielHub:ForcarAceitacao()
    -- Código para forçar aceitação de trocas
    print("Troca aceita forçadamente")
end

-- Função para mostrar a fruta do dragão
function BielHub:MostrarFrutaDragao()
    -- Código para mostrar a fruta do dragão
    print("Mostrando fruta do dragão")
end

-- Inicialização do hub
function BielHub:Iniciar()
    print("Biel Hub iniciado")
    self:CongelarTrocas()
    self:ForcarAceitacao()
    self:MostrarFrutaDragao()
end

-- Iniciar o Biel Hub
BielHub:Iniciar()
