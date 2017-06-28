using UnityEngine;
using System;
using System.Collections;

private class Atomo
{
    int ID, elec, neu, pro;
    public GameObject[] neutrones;
    public GameObject[] electrones;
    public GameObject[] protones;

    int main()
    {
        ID = Crear.IDs; // Pedir ID al usuario
        elec = ID;// La ID es el numero atómico, que coincide siempre con el numero de protones y electrones
        pro = elec;
        neu = Listas.Neutrones(ID);//Pedir la cantidad de neutrones

        InvPart();
        capas();
    }

    void capas()
    { 
        
    }

    void InvPart()
    {
        int i=0;

        for (i = 0; i < neu; i++)
        {
            GameObject neutron;
            neutron = new GameObject("Proton");

            neutrones[i] = neutron;
        }

        for (i = 0; i < elec; i++)
        {
            GameObject proton;
            proton = new GameObject("Proton");

            protones[i] = proton;

            GameObject electron;
            electron = new GameObject("Electron");

            electrones[i] = electron;
        }
    }
}
