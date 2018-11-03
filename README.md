# Sha
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp3
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {
          
        }

        private void button1_Click(object sender, EventArgs e)
        {
            
            string Strname = Showtext.Text;
            lblmsg.Text = "Hello " + Strname+"!";
        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {
            
        }

        private void label3_Click(object sender, EventArgs e)
        {
         
        }

        private void checkBox1_CheckedChanged(object sender, EventArgs e)
        {
            lblmsg.Visible = false;
        }

        private void checkBox2_CheckedChanged(object sender, EventArgs e)
        {
            lblmsg.Visible = true;
        }

        private void button1_Click_1(object sender, EventArgs e)
        {
            Area.Text =Convert.ToString(Convert.ToInt32(Length.Text)*Convert.ToInt32( Width.Text));
            Perimeter.Text = Convert.ToString((Convert.ToInt32(Length.Text) + Convert.ToInt32(Width.Text)) * 2);
        }

        private void label2_Click(object sender, EventArgs e)
        {

        }
    }
}

