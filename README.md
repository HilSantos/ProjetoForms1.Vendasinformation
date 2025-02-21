# ProjetoForms1.Vendasinformation
Criar as propriedades dos dados das vendas.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForms1
{
    public class Vendasinformation
    {
        //atalho propfull+tab tab
        private int codigo;

  private int codigo_nome;

  public int Codigo_nome
        {
            get { return codigo_nome; }
            set { codigo_nome = value; }
        }

  private int cliente_codigo;

  public int Cliente_codigo
        {
            get { return cliente_codigo; }
            set { cliente_codigo = value; }
        }

  private int datavenda;

  public int Datavenda
        {
            get { return datavenda; }
            set { datavenda = value; }
        }

  private int valortotal;

  public int Valortotal
        {
            get { return valortotal; }
            set { valortotal = value; }
        }

  private int tipopagamento;

  public int Tipopagamento
        {
            get { return tipopagamento; }
            set { tipopagamento = value; }
        }
    }
}
