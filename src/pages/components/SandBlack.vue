<template>
    <h3 class="mt-10">Sand Black</h3>
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
                <td>{{ sandBlack50.name }}</td>
                <td>{{ sandBlack50.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack100.name }}</td>
                <td>{{ sandBlack100.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack200.name }}</td>
                <td>{{ sandBlack200.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack300.name }}</td>
                <td>{{ sandBlack300.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack400.name }}</td>
                <td>{{ sandBlack400.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack500.name }}</td>
                <td>{{ sandBlack500.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack600.name }}</td>
                <td>{{ sandBlack600.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack700.name }}</td>
                <td>{{ sandBlack700.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack800.name }}</td>
                <td>{{ sandBlack800.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ sandBlack900.name }}</td>
                <td>{{ sandBlack900.hex }}</td>
                <td>
                    <v-sheet :color="sandBlack900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    sandBlack50,
    sandBlack100,
    sandBlack200,
    sandBlack300,
    sandBlack400,
    sandBlack500,
    sandBlack600,
    sandBlack700,
    sandBlack800,
    sandBlack900,
} from 'rukkiecodes-colors';
</script>
