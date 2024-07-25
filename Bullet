package com.example.myapp;

import java.awt.Color;
import java.awt.Graphics;

public class Bullet {
    private int x, y, width, height;
    private int dy;

    public Bullet(int x, int y) {
        this.x = x;
        this.y = y;
        this.width = 5;
        this.height = 10;
        this.dy = -5;
    }

    public void draw(Graphics g) {
        g.setColor(Color.RED);
        g.fillRect(x, y, width, height);
    }

    public void move() {
        y += dy;
    }

    public int getX() {
        return x;
    }

    public int getY() {
        return y;
    }

    public int getWidth() {
        return width;
    }

    public int getHeight() {
        return height;
    }
}
