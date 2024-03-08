<template>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ white.name }}</td>
                <td>{{ white.hex }}</td>
                <td>
                    <v-sheet :color="white.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>

            <tr>
                <td>{{ black.name }}</td>
                <td>{{ black.hex }}</td>
                <td>
                    <v-sheet :color="black.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red.name }}</td>
                <td>{{ red.hex }}</td>
                <td>
                    <v-sheet :color="red.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green.name }}</td>
                <td>{{ green.hex }}</td>
                <td>
                    <v-sheet :color="green.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue.name }}</td>
                <td>{{ blue.hex }}</td>
                <td>
                    <v-sheet :color="blue.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import { black, blue, green, red, white } from 'rukkiecodes-colors';
</script>
