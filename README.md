GiYuCraft
=========

Plugin de GiYuCraft -Basico


Códificación Binary:

package giyuchat;

import org.bukkit.command.Command;
import org.bukkit.command.CommandSender;
import org.bukkit.plugin.java.JavaPlugin;





public class GiYuChat extends JavaPlugin{

    @Override
    public void onEnable(){
        
        getLogger().info("Plugin GiYuChat Activado Correctamente");
    }
    
    
    
    @Override
    public void onDisable(){
        
        getLogger().info("Plugin GiYuChat Desactivado Correctamente");
        
    }
    
    @Override
    
    public boolean onCommand(CommandSender sender, Command cmd, String label, String[] args){
      if(cmd.getName().equalsIgnoreCase("giyu")){
          
          sender.sendMessage("[GiYuCraft Server Development] - GiyuCraft It's Swaggy");
      }
        
        
        
        
        return false;
    }
}
