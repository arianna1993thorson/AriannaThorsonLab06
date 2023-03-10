using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class EnumTest : MonoBehaviour
{
    public enum GameState {Ready = 1, Playing = 2, Paused = 3, GameOver = 4, Exit = 5 }
    public GameState gameState;
    public enum Levels { Menu = 0, EasyLevel = 1, NormalLevel = 2, HardLevel = 3, SampleScene = 4 }
    public Levels gameLevels;

    // Start is called before the first frame update
    void Start()
    {
        gameState = GameState.Ready;
        gameLevels = Levels.Menu;
    }

    // Update is called once per frame
    void Update()
    {

        switch (gameState)
        {
            case GameState.Ready:
                Debug.Log((int)GameState.Ready);
                break;
            case GameState.Playing:
                Debug.Log((int)GameState.Playing);
                break;
            case GameState.Paused:
                Debug.Log((int)GameState.Paused);
                break;
            case GameState.GameOver:
                Debug.Log((int)GameState.GameOver);
                break;
        }

        switch (gameLevels)
        {
            case Levels.Menu:
                Debug.Log((int)Levels.Menu);
                break;
            case Levels.SampleScene:
                Debug.Log((int)Levels.SampleScene);
                break;
            case Levels.EasyLevel:
                Debug.Log((int)Levels.EasyLevel);
                break;
            case Levels.NormalLevel:
                Debug.Log((int)Levels.NormalLevel);
                break;
            case Levels.HardLevel:
                Debug.Log((int)Levels.HardLevel);
                break;
        }

        //new GameState Exit = 5;

    }
}
